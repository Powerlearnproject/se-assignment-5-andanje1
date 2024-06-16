[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284069&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   Steps to Download and Install Visual Studio Code on Windows 11:
Prerequisites include:
Ensure you have Windows 11 installed on your machine.
You may need administrative privileges to install software.

Download VS Code:
Go to the official Visual Studio Code website.
Click on the "Download for Windows" button. This should automatically detect your operating system.

Install VS Code:
Once the download is complete, open the installer (usually named something like VSCodeSetup-x64-x.x.x.exe).
Follow the installation prompts:
Accept the license agreement.
Choose the installation location.
Select additional tasks such as creating a desktop icon or adding VS Code to your PATH.
Click Install to begin the installation process.
Once the installation is complete, click Finish.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   Initial Configurations and Settings:
Theme and Appearance:
Open VS Code.
Navigate to File > Preferences > Color Theme to choose a preferred theme (e.g., Dark+, Light+, etc.).

Settings Sync:
If you use VS Code on multiple machines, you can enable Settings Sync via File > Preferences > Settings Sync.

Install Key Extensions:
Navigate to the Extensions view by clicking on the Extensions icon in the Activity Bar or using Ctrl+Shift+X.
Install recommended extensions such as:
Prettier for code formatting.
ESLint for linting JavaScript.
Python (if working with Python).
Live Server for a live preview of web projects.
GitLens for enhanced Git capabilities.

Editor Settings:
Navigate to File > Preferences > Settings or press Ctrl+,.
Adjust settings like editor.tabSize, editor.fontSize, and editor.wordWrap as per your preference.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Main Components:
Activity Bar:
Located on the far left, it provides quick access to different views like Explorer, Search, Source Control, Run and Debug, Extensions, etc.

Side Bar:
This is where different views (from the Activity Bar) are displayed, such as the file explorer, search results, and source control.

Editor Group:
The central area where you open and edit your files. You can split the editor into multiple groups to view and edit multiple files side by side.

Status Bar:
Located at the bottom, it provides information about the current file and project, such as line/column number, Git branch, errors/warnings, encoding, and language mode.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   The Command Palette in Visual Studio Code is a powerful feature that provides quick access to various commands and functions without the need for navigating through menus or using the mouse. 

   Accessing the Command Palette:
Press Ctrl+Shift+P (or F1) to open the Command Palette.

Common Tasks:
Searching and executing commands like Open File, Save, Toggle Terminal.
Changing settings, such as Preferences: Open Settings (UI).
Running tasks and debugging configurations.
Installing extensions via Extensions: Install Extensions

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   Role of Extensions and How to Manage Them:
Role:
Extensions enhance the functionality of VS Code by adding new features, such as language support, debuggers, linters, and more.

Finding and Installing Extensions:
Go to the Extensions view by clicking on the Extensions icon in the Activity Bar or using Ctrl+Shift+X.
Search for extensions by name or keyword.
Click Install on the desired extension.

Managing Extensions:
View installed extensions and disable, uninstall, or configure them as needed from the Extensions view.
Essential Extensions for Web Development:

Prettier: Code formatter.
ESLint: Linting JavaScript and TypeScript.
Live Server: Launch a local development server with live reload feature.
Debugger for Chrome: Debug your JavaScript code in the Chrome browser.
Path Intellisense: Autocomplete for file paths.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   Opening and Using the Integrated Terminal:g
Opening the Terminal:
Use Ctrl+ (or View > Terminal) to open the integrated terminal.

Advantages:
Keeps you within the VS Code environment without switching to an external terminal.
Supports multiple terminal sessions.
Integrates with the current workspace, making it easy to run project-specific commands.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   Creating, Opening, and Managing Files and Folders:

Creating Files/Folders:
Right-click in the Explorer view (Side Bar) and choose New File or New Folder.

Opening Files:
Double-click on a file in the Explorer view.
Use File > Open File or Ctrl+O to open a file from the filesystem.

Managing Files/Folders:
Use the context menu in the Explorer view to rename, delete, or move files and folders.
Drag and drop files within the Explorer to reorganize.

Navigating Between Files:
Use Ctrl+P to quickly open files by name.
Use Ctrl+Tab to switch between open files.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   Customizing Settings:
Finding Settings:
Navigate to File > Preferences > Settings or press Ctrl+,.

Changing Theme:
File > Preferences > Color Theme or use the Command Palette (Ctrl+Shift+P) and type Color Theme.

Changing Font Size:
Go to Settings, search for fontSize, and set your preferred font size.

Changing Keybindings:
Navigate to File > Preferences > Keyboard Shortcuts or press Ctrl+K Ctrl+S.
Modify keybindings by clicking on the action and entering a new key combination.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   Setting Up and Starting Debugging:
Open a Project:
Open the folder containing your project files.

Configure Debugging:
Click on the Run and Debug icon in the Activity Bar or press Ctrl+Shift+D.
Click create a launch.json file to configure debugging settings for your project.

Start Debugging:
Set breakpoints in your code by clicking in the gutter next to the line numbers.
Press F5 to start debugging.
Use the Debug toolbar to step through code, continue execution, and view variables.

Key Debugging Features:
Breakpoints
Step over, step into, and step out
Watch expressions
Variable and call stack view
Console output

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    Integrating Git with VS Code:
Initializing a Repository:
Open the project folder.
Click on the Source Control icon in the Activity Bar.
Click Initialize Repository.

Making Commits:
After making changes to your files, go to the Source Control view.
Stage changes by clicking the + icon next to each file or Stage All Changes.
Enter a commit message and click the checkmark icon to commit.

Pushing Changes to GitHub:
Open the Command Palette (Ctrl+Shift+P).
Type Git: Add Remote and add the remote URL for your GitHub repository.
Use Ctrl+Shift+P and type Git: Push to push your commits to GitHub.

References 

Johnson, B. (2019) Visual studio code: End-to-end editing and debugging tools for web developers. INpolis, IN: Wiley. 
Install and use visual studio code on Windows 10 (VS code) (2019) YouTube. Available at: https://youtu.be/MlIzFUI1QGA?si=mcFYUnCAmmkv7h75 (Accessed: 16 June 2024). 

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

