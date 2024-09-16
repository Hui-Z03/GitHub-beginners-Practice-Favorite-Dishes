# GitHub-beginners-Practice-Favorite-Dishes
For beginners to practice Git and GitHub

Welcome to the GitHub Beginners Practice: Favorite Dishes project!

This simple project is designed to help beginners learn how to use Git and GitHub. 
You will practice collaborating by adding your favorite dish to a shared Python file.

Instructions
1. Fork the Repository
    Click the "Fork" button in the upper right corner to create a copy of the repository in your own GitHub account.
2. Clone the forked repository to your local computer
    Go to your GitHub account, open the forked repository, click on the green "code" button and then click the copy to clipboard icon.
    Open a terminal and run the following git command: git clone "url you just copied"
3. Add Your Favorite Dish
    Navigate to the project directory: cd favorite-dishes
    Create a branch using the git switch command: git switch -c your-new-branch-name
   Make changes to "favorite_dishes.py"
    Open the favorite_dishes.py file in a text editor. At the end of the file, add:
   ```
   print('Your Favorite Dish')
   # Your Name
   ```
   Replace 'Your Favorite Dish' with the name of your favorite dish. Replace Your Name with your actual name.
4. Commit and Push Your Changes
   git add favorite_dishes.py
   git commit -m "Add favorite dish by Your Name"
5. Push changes to GitHub
   Push your changes using the command git push: git push -u origin your-branch-name
6. Submit your changes for review
   go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.
   submit the pull request.
    I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.


初学者练习 Git 和 GitHub
欢迎来到 GitHub 初学者练习项目：最喜爱的菜肴！

这个简单的项目旨在帮助初学者练习如何使用 Git 和 GitHub。
您将通过向共享的 Python 文件中添加您最喜爱的菜肴来练习协作。

操作指南
1. Fork 仓库
点击右上角的 "Fork" 按钮，将仓库复制到您自己的 GitHub 账户中。

2. 将 Fork 的仓库克隆到您的本地电脑
进入您的 GitHub 账户，打开您 Fork 的仓库。
点击绿色的 "Code" 按钮，然后点击复制到剪贴板的图标。

打开终端，运行以下 git 命令： git clone "您刚刚复制的 URL"

3. 添加您最喜爱的菜肴
进入项目目录：cd favorite-dishes
使用 git switch 命令创建一个新分支：git switch -c your-new-branch-name
修改 favorite_dishes.py
在文本编辑器中打开 favorite_dishes.py 文件。
在文件末尾添加：

print('Your Favorite Dish')
"# Your Name"

将 'Your Favorite Dish' 替换为您最喜爱的菜名
将 Your Name 替换为您的名字

4. 提交并推送您的更改
git add favorite_dishes.py
git commit -m "Add favorite dish by Your Name"

5. 将更改推送到 GitHub
使用以下命令推送您的更改：git push -u origin your-branch-name

6. 提交您的更改以供审核
前往您在 GitHub 上的仓库，您会看到一个 "Compare & pull request" 按钮。点击它。
提交 pull request。
我会将你们所有的更改合并到这个项目的主分支。一旦更改被合并，您将收到一封通知邮件。

