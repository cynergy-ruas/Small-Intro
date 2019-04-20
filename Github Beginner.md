---
typora-copy-images-to: ./
typora-root-url: ./
---

# GitHub for Beginners

> ***Author: Chirag Mittal*** 	***Batch: 7***

------

GitHub is a web platform which provides free cloud storage and hosting service for version control system called Git. 

Git is a command-line tool developed by *Linus Trovalds* for versioning projects and collaboration in team. GitHub makes it easier to do so by providing a GUI and also remote hosting capabilities. 

## How to create an account on GitHub

1. Go to [Github Signup page](https://github.com/join?source=header-home)

   ![img](https://www.wikihow.com/images/2/2c/Join-github-1.jpg)

   

2. Fill in all the user details (username, email address, and password)

3. Click on "Create an account" button. (You will be redirected to **Choose your plan** tab)

4. In **Choose your plan** tab: there are two options 1) Free and 2) Pro. Select Free plan and click on **Continue**.

   ![1551630745091](/1551630745091.png)

5. Upon clicking on Continue, you will be redirected to **Personalize your experience** tab. If you have time you can fill it else you can skip it too.

   ![1551630978797](/1551630978797.png)

6. *Click on Submit button* and you are finished!!!

## How to upload first project

> Before uploading a project. Make sure you are signed in

1. Click on **New** button the top-left corner of your main Github page

   ![1551631550802](/1551631550802.png)

2. Upon clicking on New button, you will be redirected to *Create New Repository* Page. Here, enter the name of your repository and description (optional). 

   ![1551631914035](/1551631914035.png)

3. Choose whether you want to make it Public or Private repository. 

4. If you are creating a repository for an existing project you need not initialize it with README but if you are making a new repository initialize it with README. Click on **Create repository** when you are done.

5. Upon clicking on Create repository button, you will be redirected to your project. (There will be a README file if you have checked the initialize with README)

   ![1551632025123](/1551632025123.png)

   ------

   ***There are two ways of uploading projects***

   ### GUI way

6. For uploading the files of your project. Click on **Upload files** button. You will be redirected to upload files page.

   ![1551632438159](/1551632438159.png)

7. Add files to the page by Choosing or Dragging them on the page. Add a commit message (optional)

8. Click on **Commit changes** button and your files will be there. 

   ------

   ### CLI way

   > This way requires Git Bash installed in your system

6. Open Git Bash

7. Change the current working directory to your project directory by using 

   ```bash
   cd Relative/ProjectDirectory/Path
   ```

8. Initialize a new local repository 

   ```bash
   git init
   ```

9. Add all the files to this repository. This will stage all the files for commit

   ```bash
   git add .
   ```

10.  Commit the staged files and give a message. This prepares the files to be pushed to your remote repository

11. Add the URL to you remote repository; URL can be find at the Github's repository homepage

    ![1551633225706](/1551633225706.png)

    ```bash
    git remote add origin https://github.com/mittalchirag/SampleProject.git
    ```

12. Push the changes to remote repository on Github

    ```bash
    git push origin master
    ```

13. All the files now will be visible on the repository page. **You are done!!!**

    > The GUI way is a bit daunting to do as you have to select each file and then its really hard to create folders in GUI way.

------

