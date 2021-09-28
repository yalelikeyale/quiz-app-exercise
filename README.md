# quiz-app-exercise
*Intro to web development and behavioral tracking*

## **Getting Started**

### Setting up your Development Environment

1. **Create a Github Account**
- [SignUp Here](https://github.com/signup)
- [Fork This Repo](https://github.com/yalelikeyale/quiz-app-exercise)
  - [How to fork repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

2. **Setting up your Terminal** 
*[Setting up your development environment. Look ma, code stuff!]*(https://chiamakaikeanyi.dev/how-to-configure-your-macos-terminal-with-zsh-like-a-pro/)
*The following steps are the necessary steps pulled from the above linked blog post for this project. If you'd like to continue playing around with customizing your terminal experience, feel free to follow all of the steps in the blog post. However, the below steps are the only ones which are required for this project*

- Open your Mac Terminal 

- Make sure Homebrew is installed
`brew help`

- Install iTerm2
`brew cask install iterm2`

- Install Oh My Zsh! 
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

- Open the iTerm2 App, right click, keep in dock

3. **Setting up VS Code**

- [Install VS Code IDE](https://code.visualstudio.com/download)
- [Switch default terminal to iTerm2](https://saiankit30.medium.com/how-to-change-the-integrated-terminal-in-vs-code-from-default-to-pro-iterm-ish-5c958e13aada)

`Manage Widget >> Settings >> Features >> Terminal >> set 'Explorer Kind' to 'external' and set 'Osx Exec' to 'iTerm.app'`

- Enter `Cmd+Shift+P` and then find and run `Shell Command: install 'code' command in '$PATH'`

- Open iTerm and create and save a directory for this project to your desktop:
  1. Enter `mkdir ~/Desktop/proserv_enablement` into the terminal
  2. Enter `cd ~/Desktop/proserv_enablement` into the terminal
  3. Enter `echo $PWD` into the terminal and the output should be something like `/Users/your_user/Desktop/proserv_enablement`
  4. If above looks correct, now enter `code` into the terminal. This should open up VS Code from the appropriate directory. 


- [Add Web Dev Extensions](https://codeforgeek.com/best-visual-studio-code-extensions-web-development/)

  **Required**
  - GitLens
  - Github Pull Requests and Issues

  **Nice to Have**
  - Javascript ES6 Snippets
  - CSS Peek
  - CSS Intellisense for HTML
  - Auto Close Tag
  - HTML Boiler Plate
  - Live Server
  - Prettier
  - Rest Client
  - Path Intellisense
  - ES Lint


4. **Integrate GitHub with VS Code**
  - Enter `Cmd+Shift+P` and then find and run `Git: Clone` 
  - You should see `Clone from GitHub` pop up as an option. Click that and authenticate the integration so that VS Code has permission to push and pull from GitHub.
  - Now lookup and find the repo you forked earlier to download
  - From the top nav panel "Code, File, Edit, Selection...", click `Terminal` and open `New Terminal`
  - Within the terminal, run `open index.html`. This should open the app with your default browser... and yes it should look awful. We are going to fix that during this tutorial. 


## Objectives of this Tutorial 

1. *Wire Static Web Page Up*
2. *Fix CSS*
3. *Install Heap*
4. *Enrich Autocaptured Data with Analytic Specific Attributes*

**!!Bonus Points!!**
5. *Swap out JSON object for Mongo Backend and deploy as Node App on Heroku*
6. *Implement CRUD tracking via success and failure callbacks*

**!!Even More Bonus Points!!**
7. *Convert to React App*
8. *Add data-testids and implement push state changes*






