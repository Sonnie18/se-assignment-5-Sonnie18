[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280555&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
    A.. Prerequisites:

             Ensure you have a stable internet connection.
            Confirm that your system meets the minimum requirements for Visual Studio Code.
    B. Download:

           Visit the Visual Studio Code website.
           Click on the Windows download link.

    C. Install:
           Once downloaded, open the installer.
           Accept the agreement and click Next.
           Choose the installation location and click Next.
           Select start menu folder and click Next.
           Choose additional tasks (e.g., add to PATH) and click Next.
           Click Install and wait for the installation to complete.
           Click Finish to launch Visual Studio Code.
(REFERENCE:Online)

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

    A. Theme and Appearance:
          Choose a comfortable theme (e.g., Dark+, Light+).
          Adjust font size and type to your preference.

    B. Editor Settings:

          Enable Auto Save to automatically save changes.
          Set Word Wrap to ‘on’ or ‘bounded’ for better readability.
          Configure Tab Size and Indentation based on your language standards.

    C.Keybindings:
          Customize keybindings (Ctrl+K Ctrl+S) for frequently used actions.

    D.Extensions:
          Prettier for code formatting.
          ESLint or TSLint for linting.
          Bracket Pair Colorizer for visualizing matching brackets.
          IntelliSense extensions for your specific programming languages.

    E. File Explorer:
          Enable File Auto Save and set the delay duration.
          Customize the sidebar to show/hide certain files or folders.

    F.Terminal Integration:
          Set up the integrated terminal with your preferred shell (e.g., PowerShell, Git Bash).
(REFERENCE:Online)

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

       A.Activity Bar:
             Located on the far left-hand side, it allows you to switch between different views and gives access to additional features like Search, Source Control, and Extensions.

       B. Side Bar:

             Displays different panels based on the selected view from the Activity Bar, such as the Explorer for file navigation, Search for finding text, and Source Control for Git operations.

       C. Editor Group:
             The central area where you can open and edit files. You can have multiple editor groups for side-by-side editing.

       D. Status Bar:
             Located at the bottom, it shows important information about the opened project and files, such as line number, encoding, language mode, and Git branch.
(REFERENCE:Online)

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

     DEFINATION-The Command Palette in VS Code is a feature that allows you to quickly access a wide range of commands and features. You can access it by pressing Ctrl+Shift+P or F1.

     COMMON TASKS 
       *Opening files or projects (Open File, Open Folder).
       *Managing extensions (Install Extension, Disable Extension).
       *Changing settings (Preferences: Open Settings).
       *Running tasks (Tasks: Run Task).
       *Accessing Git commands (Git: Commit, Git: Pull). 
(REFERENCE:Online)   

5. Extensions in VS Code:
   -Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

     DEFINATION-Extensions in VS Code enhance its functionality by adding new features or integrating with other tools and services. They play a crucial role in customizing the development environment to suit specific needs.

     I.Finding Extensions:
         Use the Extensions view by clicking on the Extensions icon in the Activity Bar or pressing Ctrl+Shift+X.
Search for extensions by name, functionality, or popularity.

     II.Installing Extensions:
        Click on an extension to view its details.
Press the Install button to add it to your VS Code.

     III.Managing Extensions:
        Update, disable, or uninstall extensions via the Extensions view.
Configure extension settings through the user or workspace settings.

     IV.Essential Extensions for Web Development:
           *Live Server: Launches a local development server with live reload feature.
           *Debugger for Chrome: Integrates Chrome’s developer tools into VS Code.
           *Prettier: Code formatter that supports many languages.
           *ESLint: Linter for JavaScript and TypeScript.
           *Auto Rename Tag: Automatically renames paired HTML/XML tags
 (REFERENCE:Online)  


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   OPENING VS CODE TERMINAL
        i.Press Ctrl+` or select View > Terminal from the menu bar.
        ii.A terminal panel will appear at the bottom of the window.
        iii.You can type and execute commands just like in an external terminal.

   ADNAVTAGES COMPARED TO AN EXTERNAL TERMINAL
        *Convenience: Accessible directly within the editor; no need to switch windows.
        *Context-Aware: Automatically opens in the current project’s directory.
        *Customizable: Supports multiple terminal instances and different shell types.
        *Integrated Workflow: Allows you to run scripts, commit code, and use CLI tools without leaving VS Code.
(REFERENCE:Online)


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
     
      CREATING FILE/FOLDER:
        *Right-click in the Explorer pane and select New File or New Folder.
        *Use the shortcut Ctrl+N to create a new file.

       OPENING FILES:
        *Click on a file in the Explorer pane to open it.
        *Use Ctrl+P to open the Quick Open dialog and search for files.

       MANAGING FOLDER:
        *Add folders to your workspace by right-clicking in the Explorer pane and selecting Add Folder to Workspace.
        *Remove folders by right-clicking on them and selecting Remove Folder from Workspace.

       NAVIGATING FILES/REPOSITORIES:
        *Use tabs to switch between open files.
        *Use Ctrl+Tab to cycle through active files.
        *Use the breadcrumbs at the top of the editor to navigate file paths.
(FERERENCE:Online)


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

      A.Opening the Settings panel with Ctrl+, or by selecting File > Preferences > Settings.

      B.Searching for specific settings in the search bar at the top of the Settings panel.

            
        CHANGING THEME:
     Go to Color Theme under Appearance and select your preferred theme from the list.

        CHANGING FONT SIZE:
     Find Font Size under Editor: Font and set your desired font size.

      CUSTOMIZING KEYBUILDINGS:
     *Open the Keyboard Shortcuts editor with Ctrl+K Ctrl+S or by selecting File > Preferences > Keyboard Shortcuts.
     *Search for a command and click on the keybinding to set a new shortcut.
(REFERENCE:Online)

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   i.Open the program file you want to debug.
   ii.Go to the Run view by clicking on the Run icon in the Activity Bar or pressing Ctrl+Shift+D.
   iii.Click on create a launch.json file to set up your debug configurations.
   iv.Select the environment that matches your programming language (e.g., Node.js, Python).
   v.Set breakpoints in your code by clicking on the left margin next to the line numbers.
   vi.Press F5 or click on the green Start Debugging button to begin.
   vii.Key debugging features in VS Code:
       *Breakpoints: Pause code execution at specific points.
       *Call Stack: Shows the stack trace of active functions.
       *Variables: Inspect variables and their values.
       *Watch: Evaluate expressions and monitor their values over time.
       *Step Over/Into/Out: Control execution flow during debuggin
(REFERENCE:Online)


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    a.Open the folder containing your project in VS Code.
    b.Initialize a Git repository by opening the integrated terminal and running git init.
    c.The Source Control view will activate, showing changes and options for version control.

         MAKING COMITS:
    *Stage changes by clicking on the ‘+’ icon next to changed files in the Source Control view.
    *Enter a commit message in the input box and press Ctrl+Enter to commit.

         

Add a remote repository with git remote add origin [URL].
Push your commits by clicking on the … icon in the Source Control view and selecting Push.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

