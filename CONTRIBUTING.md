Got any cool ideas for the club? 
===

- This is the (relatively simple) procedure for suggesting things:
  1. Goto http://github.com/bakercs/about and click the "fork" button in the upper right - this makes a copy of the repository and puts it under your username, so `http://github.com/bakercs/about` becomes `http://github.com/[YOUR USERNAME HERE]/about`.
  
  ![fork button](assets/fork.jpg)

  2. Make whatever edits you'd like:
    - This can be done right on the site (go to the file you'd like to edit, and click on the pencil icon, edit, and save)

    - Alternatively, you can download Github (windows.github.com, mac.github.com, or 'apt-get install git' for linux)
      - For windows, open the application titled git shell, and on mac/linux, open terminal
      - `git clone https://github.com/bakercs/about.git`, and `cd about`
      - run the command `pwd` to tell you what folder you're in
      - go to that folder in windows explorer / finder / a file browser
      - start editing whatever files you'd like with notepad on windows, or textedit on mac, or whatever else
      - After editing, `git add -u`, then `git commit -m "a message describing what you did"` , and lastly, `git push origin master`


    - What's in each file:
      - topics.md contains all the topic ideas I've had - any suggestions for what to at future meetings / future topics should go here.
      - README.md is shown below the files ("Welcome to the first meeting of the Baker CS Club!")

  3. Go back to `http://github.com/[YOUR USERNAME HERE]/about`, and click on this ​green button right above the file list:
  
  ![pull request icon](assets/pr.png)

  4. Click "Create Pull Request" - type in a small description, if you'd like, and create it.

  5. And, done! I'll take a look and if what you've said looks up-to-par I'll put it back into the main repo, that is, `bakercs/about`. Also, after I've merged you're edits into the main repo, feel free to delete the fork you made in step 1 (Click on settings, and look at the bottom under Danger Zone).

