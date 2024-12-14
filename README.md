[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282217&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
   
       NAME: Ajiboye Oluwatobi Samuel
Questions:
1.	Installation of VS Code:
I navigated to https://code.visualstudio.com/ and I downloaded the vs code from the website. After download, I ran the download as administrator and installed into  my desired folder.
2.	First-time Setup:
•	After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions
After installing, font size can be adjusted according to preference, also, the theme colour of the app. The important most important extension to download is python and others like dart, data wrangler, code runner, flutter, Django. Jupyter, pylance.
3.	User Interface Overview:
o	Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
The activity bar shows the ongoing folders of project the user is working on. The side bar contains various buttons like extensions, search, explorer, source control, Debug, testing. The editor group bar is where user can majorly make actions concerning files. View, open, create new files, control the app view and selection, open terminals, etc.
4.	Command Palette:
o	What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
The Command Palette provides access to many commands. You can run editor commands, open files, search for symbols, and see a quick outline of a file, all using the same interactive window.  Ctrl+ shift + P opens the command palette and enables you to navigate to any file or symbol by typing its name.


5.	Extensions in VS Code:
o	Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
Extensions in vs code can be found in the extension tab on the side bar. User can search for desired extension and install. After installation, user can manage extensions by choosing to uninstall, restart, stop etc. Examples of extensions are python, dart, data wrangler, code runner, flutter, Django. Jupyter, pylance. Extensions functions as the ability to add languages, debuggers, and tools to your installation to support your development workflow.
6.	Integrated Terminal:
o	Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
The integrated terminal can be opened by tapping on the three dots on the top bar and selecting “terminal” then tapping on a new terminal. This terminal is better because it has its own integrated extensions of PowerShell, gitbash admit others.
7.	File and Folder Management:
o	Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
A file and folder ca either be created using git bash and then moved into vs code, A file and folder can also be created inside vs code by tapping on the file button on top. Here the file activities can also be managed as user wants.
8.	Settings and Preferences:
o	Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
The settings can be found on the side bar. User can change font size, theme and keybindings. When user taps on the settings button, user can see the theme button to set desired theme. After tapping on the settings button, user taps on settings again and can be able to edit font.
9.	Debugging in VS Code:
o	Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
1. Install Visual Studio Code
2. Install Necessary Extensions
•	Open your project or create a new file 
•	Save your new file with the appropriate file extension 
4. Write Your Code
•	Write a simple program. For example, a simple Python program:
5. Configure the Debugger
•	Click on the Debug icon in the Activity Bar on the side of the window or press Ctrl+Shift+D.
•	Click on the gear icon to open the launch.json file. If you don't see a launch.json file, you can create one by clicking on "create a launch.json file" link in the Debug panel.
For a Python program, your launch.json might look like this:
•	Open the file you want to debug.
•	Click in the gutter to the left of the line numbers to set breakpoints. A red dot will appear to indicate a breakpoint.
7. Start Debugging
•	Click on the green play button in the Debug panel, or press F5 to start debugging.
•	The program will run, and execution will pause at any breakpoints you've set.
Key Debugging Features in VS Code
1.	Breakpoints:
o	Set breakpoints by clicking in the gutter next to the line numbers. This allows you to pause execution at specific lines of code.
2.	Watch Expressions:
o	Monitor specific variables or expressions by adding them to the Watch panel. This helps you keep an eye on their values as you step through the code.

3.	Call Stack:
o	View the call stack to understand the sequence of function calls that led to the current point in the program. This helps in diagnosing the flow of execution.
4.	Variable Inspection:
o	Inspect the values of variables in the current scope in the Variables panel. This includes local variables, global variables, and closure variables.

10.	Using Source Control:
o	How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
Below are the steps to initialize a Git repository, make commits, and push changes to GitHub.
1. Install Git
First, ensure that Git is installed on your system.
Verify the installation by running the following command in your terminal: git –version
2. Open VS Code
Launch VS Code and open your project folder.
3. Initialize a Git Repository
•	Open the Command Palette by pressing Ctrl+Shift+P 
•	Type Git: Initialize Repository and select it.
•	Choose the folder you want to initialize as a Git repository. This will create a .git folder in your project directory.
4. Stage Changes
•	Click on the Source Control icon in the Activity Bar on the side of the window.
•	You will see a list of changes in your project. Click on the + icon next to each file to stage individual files, or click on the + icon at the top to stage all changes.
5. Make a Commit
Once your changes are staged, you can commit them by pressing:
git add .
git commit -m "Your commit message"
6. Push Changes to GitHub
To push your changes to GitHub, you need to link your local repository to a remote repository on GitHub.
Step 1: Create a Repository on GitHub
•	Go to Github and log in to your account.
•	Click on the + icon in the upper right corner and select New repository.
•	Enter a name for your repository and click Create repository.
STEP 2: In Git bash, input: git remote add origin https://github.com/your-username/your-repository.git
Step 3: Push Changes by entering git push -u origin master















 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

