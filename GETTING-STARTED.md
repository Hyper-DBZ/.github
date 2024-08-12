# Getting Started with Version Control

## What is Version Control?

Version control is a system that helps you track changes to your files over time. It allows you to save different versions of your work, collaborate with others, and easily revert changes if something goes wrong. For hobbyist Mugen programmers, using version control can help manage your Mugen projects efficiently.

## Why Use Version Control?

- **Track Changes**: See who made changes and why.
- **Revert Changes**: Easily undo mistakes.
- **Collaborate**: Work with others without overwriting each other’s work.
- **Backup**: Keep your work safe from accidental loss.

## Getting Started with Git

### What is Git?

Git is a popular version control system that helps you manage changes to your code and collaborate with others. It's widely used and well-supported, making it a great choice for beginners.

1.  Install Git

    #### Windows

    1. Download Git for Windows: [Download Git](https://git-scm.com/download/win)
    2. Run the Installer: Follow the installation prompts. You can use the default settings.

    #### macOS

    1. Install Git Using Homebrew: Open Terminal and run:

       ```sh
       brew install git
       ```

       If you don't have Homebrew installed, get it from [brew.sh](https://brew.sh/).

       **Alternative**: Download Git directly from [Git SCM](https://git-scm.com/download/mac) and follow the installer instructions.

    #### Linux

    1. Open Terminal and run the following command:

       ```sh
       sudo apt-get install git
       ```

       (For Debian-based distributions like Ubuntu. Use yum or dnf for other distributions.)

       **Alternative**: Install Git from your distribution’s package manager or from [Git SCM](https://git-scm.com/download/linux).

2.  Set Up Git

    After installation, you'll need to configure Git with your name and email. Open your command line or terminal and run the following commands:

    ```sh
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

3.  Create a New Repository

    A repository (or "repo") is where Git stores your project's files and version history.

    1. Navigate to Your Project Folder: Use the command line to go to your Mugen project directory.

       ```sh
       cd path/to/your/project
       ```

    2. Initialize Git: Run the following command to create a new Git repository in your project folder:

       ```sh
       git init
       ```

4.  Add Files to Your Repository

    To start tracking your files, you need to add them to the Git repository.

    1. Add Files: Use the following command to stage all files for commit:

       ```sh
       git add .
       ```

       (The . adds all files in the directory. You can specify individual files if needed.)

    2. Commit Changes: Save the staged files to your repository with a commit message:

       ```sh
       git commit -m "Initial commit"
       ```

5.  Basic Git Commands

    Here are some basic commands you’ll use frequently:

    - Check Status: See which files have changed or are staged for commit.

      ```sh
      git status
      ```

    - View History: View the commit history of your project.

      ```sh
      git log
      ```

    - Make Changes: Edit files in your project as needed. After making changes, use:

      ```sh
      git add <filename>
      git commit -m "Describe your changes"
      ```

    - View Changes: See what changes have been made since the last commit.
      ```sh
      git diff
      ```

6.  Using GitHub for Remote Repositories

    GitHub is a platform where you can host your Git repositories online, collaborate with others, and backup your work.

    1. Create a GitHub Account: Sign up at GitHub.

    2. Create a New Repository on GitHub: Click on the "New" button in your repositories section.

    3. Connect Your Local Repository to GitHub:
       ```sh
       git remote add origin https://github.com/yourusername/your-repository.git
       git branch -M main
       git push -u origin main
       ```
       (Replace yourusername and your-repository with your actual GitHub username and repository name.)

7.  Resources

    Here are some helpful resources to learn more about Git and version control:

    - [Git Cheat Sheet](GIT-CHEAT-SHEET.md)
    - [Git Documentation](https://git-scm.com/doc)
    - [GitHub Guides](https://guides.github.com/)
    - [Pro Git Book](https://git-scm.com/book/en/v2)

## Conclusion

Version control with Git is a powerful tool that can greatly improve how you manage your Mugen projects. By following this guide, you should now have a basic understanding of how to get started with Git, set up a repository, and begin tracking your changes.

Feel free to reach out with any questions or if you need further assistance. Happy coding!
