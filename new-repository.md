# Git

1. Open https://github.com/
1. Sign-in
1. In upper right corner click your `account icon`, then choose `Your Repositories`
1. Click the green `New` button to create a new repository
1. Fill in the `Repository name`. No spaces.
1. Click the checkbox `Add a README file`
1. Click the green button `Create Repository` at the bottom of the screen
1. Copy the url for the repository to your clipboard

   1. Click in your browser's address bar and copy it
   1. Or click the green code button and then click the copy icon next to the URL

1. Open a terminal in the directory where you want to work (usually LearnToCode)
   1. Windows: Right-click in Windows File Explorer and choose `Git Bash Here`
   1. MacOS: Right-click then choose `New Terminal at Folder`
      - Note if you are on an older MacOS version you may need to manually `cd` to the directory
1. Clone the repository by running the following command.
   ```
   git clone https://github.com/yourusername/yourrepository.git
   ```
   > This will create a folder/directory inside of your work folder (Ex. LearnToCode/yourrepository) with your repository
   > You can safely ignore the following warning
   ```
   warning: You appear to have cloned an empty repository.
   ```
1. Open your repository's corresponding folder/directory in VS Code
1. Make changes to your code (add files, edit files, delete files etc..)
1. Open your repository's corresponding folder/directory in a terminal (Git Bash on Windows)
1. Stage your changes
   ```
   git add .
   ```
1. Commit your changes
   ```
   git commit -m "your message about commit contents"
   ```
1. Sync/Push your changes up to Github
   ```
   git push origin main
   ```
1. Repeat the last 5 steps as you continue to work on your code
