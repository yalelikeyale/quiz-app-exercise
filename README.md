# quiz-app-exercise
*Intro to web development and behavioral tracking*

## **Getting Started**

### Setting up your Development Environment

1. **Create a Github Account**
- [SignUp Here](https://github.com/signup)
- [Fork This Repo](https://github.com/yalelikeyale/quiz-app-exercise)
  - [How to fork repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

2. **Setting up your Terminal** 

[Setting up your development environment. Look ma, code stuff!](https://chiamakaikeanyi.dev/how-to-configure-your-macos-terminal-with-zsh-like-a-pro/)

*The following steps are the necessary steps pulled from the above linked blog post for this project. If you'd like to continue playing around with customizing your terminal experience, feel free to follow all of the steps in the blog post. However, the below steps are the only ones which are required for this project*

- Open your Mac Terminal 

- Make sure Homebrew is installed
`brew help`

![brew help](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/brew_help.png?raw=true)

- Install iTerm2
`brew install -- cask iterm2`

- Install Oh My Zsh! 
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

![install ohmyzsh](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/install_ohmyzsh.png?raw=true)

- If the above was successful, you should be able to run `open ~/.oh-my-zsh` and `open ~/.zshrc`

![open zshrc](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/open_zshrc.png?raw=true)

![zshrc](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/zshrc.png?raw=true)

- Open the iTerm2 App, right click, keep in dock

3. **Setting up VS Code**

- [Install VS Code IDE](https://code.visualstudio.com/download)

- Switch default terminal to iTerm2

`Manage Widget >> Settings >> Features >> Terminal >> set 'Explorer Kind' to 'external' and set 'Osx Exec' to 'iTerm.app'`

![VS Terminal Settings](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/vs_settings.png?raw=true)

- Enter `Cmd+Shift+P` and then find and run `Shell Command: install 'code' command in '$PATH'`

- Open iTerm and create and save a directory for this project to your desktop:
  1. Enter `mkdir ~/Desktop/proserv_enablement` into the terminal
  2. Enter `cd ~/Desktop/proserv_enablement` into the terminal
  3. Enter `echo $PWD` into the terminal and the output should be something like `/Users/your_user/Desktop/proserv_enablement`
  4. If above looks correct, now enter `code` into the terminal. This should open up VS Code from the appropriate directory. 

![create project directory](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/create_project_directory.png?raw=true)


- [Add Web Dev Extensions](https://codeforgeek.com/best-visual-studio-code-extensions-web-development/)

  **Required**

  - GitLens
  - Javascript ES6 Snippets
  - CSS Intellisense for HTML

  **Nice to Have**

  - CSS Peek
  - Prettier
  - Auto Close Tag
  - HTML Boiler Plate
  - Live Server
  - Rest Client
  - Path Intellisense
  - ES Lint


4. **Integrate GitHub with VS Code**

- Enter `Cmd+Shift+P` and then find and run `Git: Clone` 

![vs git clone](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/vs_git_clone.png?raw=true)

- You should see `Clone from GitHub` pop up as an option. Click that and authenticate the integration so that VS Code has permission to push and pull from GitHub.

![vs clone from github](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/vs_clone_from_github.png?raw=true)

- Now lookup and find the repo you forked earlier to download

![vs clone from github](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/vs_select_repo.png?raw=true)

- From the top nav panel "Code, File, Edit, Selection...", click `Terminal` and open `New Terminal`
- From the terminal, run `cd quiz-app-exercise`
- From the terminal, run `open index.html`. This should open the app with your default browser... and yes it should look awful. We are going to fix that during this tutorial. 

![vs terminal](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/vs_terminal.png?raw=true)

![open index](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/open_index.png?raw=true)

5. **Connect Chrome to Directory**
*[Edit Source Files in Chrome](https://www.sitepoint.com/edit-source-files-in-chrome/)*
From Chrome... with index.html being open... where the URL in Chrome looks like: `Users/{your_user}/Desktop/proserv_enablement/quiz-app-exercise/index.html` *Path Look Familiar?*... Do the following: 

1. Right click, inspect, navigate to the `Sources` tab
2. On the left panel, you should see `Page` and `Filesystem`. Click `Filesystem`
3. Click `+ Add Folder to Workspace`
4. From the finder, select the `quiz-app-exercise` folder and allow chrome access. 
5. Changes made in chrome will now be reflected within your source files saved to your computer. Yay! 

![dev tools](https://github.com/yalelikeyale/quiz-app-exercise/blob/main/images/tutorial/dev_tools.png?raw=true)

![Are we having fun yet?](https://media.giphy.com/media/LxdS7fXgbjsGc/giphy.gif)
 

## **Objectives of this Tutorial**

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


## **Wire Static Web Page Up**


## **Fix CSS**




