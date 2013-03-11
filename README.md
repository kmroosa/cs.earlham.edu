# Welcome to the cs.earlham.edu
This is the Earlham College CS Content Adminitration Groups repository

## To Contribute: 
1. Create a GitHub account if you do not have one
  * [GitHub Signup](https://github.com/signup/free)
2. Login into your GitHub if you have not already
3. Navigate to this repository - https://github.com/earlham/cs.earlham.edu
4. Click "Fork"
5. Go to your user page and notice that you have a new repository, cs.earlham.edu
6. To check out the repository:
  * If you have not already, install the GitHub software on your computer
   * Graphical:
     * Click the "Clone" button and follow the approapriate instructions: 
       * Mac Help - http://mac.github.com/help
         * Read sections 1, 2, 3, 4
       * Windows Help - http://windows.github.com/help
    * Command Line:
      * Type ```git clone https://github.com/<your username>/cs.earlham.edu.git```
      * Type ```cd cs.earlham.edu```
7. Editing Files:
  * Web:
     * You can edit files directly in GitHub by clicking on the file and then clicking "Edit"
     * When done, skip to step 9 in these instructions
  * Graphical: 
     * Navigate to the folder you cloned and edit/add your files
     * When you are done, go back to the GitHub program and "commit" your changes 
       * Refer to one of the help pages above to understand "commit"
  * Command Line: 
     * Edit/Add any files but make sure to add them with ```git add <filename>```
     * To Commit: 
         * Type: ```git commit -m "Your Commit Message"```
8. Pushing back to your fork: 
  * Graphical: 
     * Click "Sync Branch"
  * Command Line: 
     * Type: ```git push https://github.com/<your username>/cs.earlham.edu.git master```
9. Merge back to the Earlham core - https://github.com/earlham/cs.earlham.edu
  * To merge your changes back to the core, you will have to issue a "Pull Request" - refer to help pages
  * In your fork, click "Pull Request"
    * An administrator will check your code and approve or disprove it
10. When editing your code again after a push and/or pull-request
  * Graphical: 
     * Delete your fork
     * Go back to step 2 of these instructions
  * Command Line: 
     * In your fork directory, type: ```git pull https://github.com/earlham/cs.earlham.edu```
         * This will pull all the changes from the core back into your fork

