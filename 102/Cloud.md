# **Git and the cloud**

### **What is git?**

Git is a distributed version control system (DVCS) that stores data using snapshots. It provides version control and protects against data loss by storing separate snapshots for each change you make. Version control is good because it allows you to look at each different instance of your code that you have made and restore or modify based on any of those versions. It also just help you keep things organized as you continue to add more to the same file. The data protection aspect is also very nice because it makes it difficult to lose a file that has been committed. This data loss prevention is further enhanced when you set up git to replicate to a remote repository or cloud storage.

### **How does the remote repository work?**

You are able to configure git to replicate your local storage with cloud storage. This requires you to clone the remote repository to your local storage so that you can sync them together. The cloning operation is easy when using GitHub as the remote storage. Just find the URL of the desired GitHub repository and run the command `git clone URL` and it will clone the repository to your computer. Make sure that you run the command from the local directory where you want the import to go.  

Now that you have the remote storage setup, you have the ability to perform work locally on your computer using your text editor and then sync it back to the cloud storage when you are finished making changes. Whenever you want to check on the status of files in your local repository, you should run `git status` from the CLI. This will show you if there are any files that are ready to sync and if they are staged for a snapshot or ready for a push. There is an important three step process to perform when you want to upload your local changes and the easy way to remember is A-C-P.  

A is for Add. You will run `git add filename` to stage that file for a snapshot.  

C is for Commit. After adding the file, you can do `git status` to confirm that the desired files are now staged for a snapshot. Then run `git commit -m "Add details about the changes you've made here."` This will commit the changes and create a new snapshot of every file that you had staged. It is important to document details about the changes you're making in the message field when performing the commit.  

P is for Push. After you have committed the changes, you can run `git status` again to confirm that the commit was successful and you are ready to push the files to the remote repository. Run `git push origin main` to push the changes to the remote storage. If you have multiple branches in your repository, then it will be important for you to set the right target location in the push command. You should see the push complete successfully and can run `git status` to check that everything shows up to date now.  

With that you should be able to successfully setup and sync your local files to a remote repository.
