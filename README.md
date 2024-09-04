# Simple Web Design Project

Welcome to our simple web design sandbox! This project is designed to help you get started with HTML, CSS, and JavaScript in an easy-to-understand environment.

Instructions for understanding GitHub CodeSpaces are below.

In this document, you will find:
- [How to "run" your page](#running-the-project)
- [How to see your page side-by-side](#viewing-your-project)
- [Editing your files](#editing-your-project)
- [Setting up Codespaces Extensions](#adding-extensions)
- [Saving your work to version control]()

## Running the Project
1. Open the project in VS Code.
2. Click on the "Run and Debug" button on the sidebar (it looks like a play button).
3. Select "Open with Live Server" from the drop-down menu.
4. Click the green play button. This will start a local server and open your project in a web browser.
5. If this fails, you could try to [start from the terminal instead](#starting-from-the-terminal)
![play-screenshot](screenshots/play-github.png)

## Viewing Your Project
![Screenshot of Ports view](./screenshots/ports-github.png)
   - You should see a pop up asking if you want to open the page after you hit "play" to run your project. If you click on it, it will open your webpage in a new tab.
   - You can click on "Ports" at the bottom of the screen to see the web connection on your computer.
   
     If you hover over the "Forwarded Address" column, you'll see a "side-by-side" icon that will show
    the webpage inside your coding editor, or a "Globe" icon that will show the icon inside your web 
    browser in a new tab.


## Editing Your Project

- Choose the "File Explorer" tab to see your files,
  and then look for your webpage code under the "public" folder.
![img](./screenshots/github-file-editor.png)

- **index.html**: This is your HTML file. Edit it to change the structure of your web page.
- **style.css**: This is your CSS file. Modify it to change the styling of your web page.

### Files You Can Ignore

You don't need to worry about the following files and folders. They are used to set up and run your project environment:

- `package.json` and `package-lock.json`: Configuration files for Node.js.
- `node_modules`: A folder containing all the packages and dependencies for the project.
- `.vscode`: Contains configuration files for Visual Studio Code.

## Adding Extensions

You should be prompted to install extensions when this Codespace loads -- say yes and you'll
get automatic code formatting set up as well as github copilot (an AI tool to try to help you code). (To get CoPilot you'll need to have verified your student account with github)

## Saving Your Work to Version Control



## Starting from the Terminal

As an alternative to using the "Play" button, you can also
type a command to run your project locally.

1. Open the terminal in VS Code (use the "Terminal" tab at the bottom)
2. Type `npm start` and press Enter. This will start a local server and open your project in a web browser.
![Terminal Screenshot](./screenshots/terminal-github.png)

