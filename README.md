[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15286590&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   
    Clicked the  download option 
•  Install Windows 11:
•	Upgrade Installation: Run the Upgrade Assistant to upgrade from Windows 10, preserving your files and apps.
•	Clean Installation: Boot from the USB drive, follow prompts to install Windows 11, and optionally format your hard drive.
•  Set Up Windows 11: Configure settings like region, keyboard layout, network connection, and sign in with a Microsoft account or create a local account.
•  Install Drivers and Updates: After installation, install necessary drivers from manufacturers and check for Windows updates to ensure system security and performance.
![alt text](<Windows 11 update.PNG>) ![alt text](<update 2.PNG>)


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Click on the "Download for [Your Operating System]" button
Clicked the download for the windows option which is the user installer x64 Arm64
Install VS Code:
Windows: Once downloaded, run the installer (.exe file) and follow the prompts. VS Code will be installed in the default location.
•  Set Up VS Code:
•	Open Visual Studio Code once installed.
•	Customize settings and install extensions through the Extensions Marketplace as per your preferences and development needs.
•  Start Using VS Code:
•	Use VS Code to write, edit, debug, and manage your code projects efficiently.
![alt text](<vs code installation.png>)

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Install Git:
•	Windows:
o	Run the downloaded .exe file.
o	Follow the installation prompts. Use the default settings unless you have specific preferences.
o	Choose appropriate options like adjusting your PATH environment or using Git from the command line and Git Bash.
•  Configure Git:
•	Set your username and email:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
•  Verify Configuration:
•	Check your Git configuration:
git config --list
•	Verify settings like user.name, user.email, and others you've configured.
•  Start Using Git:
•	Initialize a new Git repository in your project folder:
bash
cd /path/to/your/project
git init
•	Add files, commit changes, create branches, and interact with remote repositories as needed using Git commands.
![alt text](<vs code installation-2.png>) ![alt text](<git status.png>) ![alt text](<git status-1.png>) ![alt text](<git status-2.png>) ![alt text](<git status-3.png>) ![alt text](Repository.png) ![alt text](<git commit.png>)![alt text](<git hub project .png>) ![alt text](<git hub project -1.png>)

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Install Python:
Windows:
o	Run the downloaded installer (.exe file).
o	Select "Add Python to PATH" during installation to make Python executable globally accessible.
o	Follow the installation prompts to complete the setup.
Follow the Installation Steps:
o	Choose "Install Now" for default settings.
o	Opt for "Customize Installation" for more control over features and installation paths.
 Verify Installation
	Open Command Line Interface:
o	Command Prompt or PowerShell on Windows.
Check Python Version: Type python --version or python3 --version
![alt text](<python installation.png>) ![alt text](<python final install.png>) ![alt text](<python final install-1.png>)


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

 Installing Python Packages with pip
	Verify pip Installation: Type pip --version.
	Install a Package: Use pip install package-name, replacing package-name with the desired library.
   ![alt text](<python final install-2.png>)
  
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   	Navigate to the Downloads Section:
o	Click on "Downloads" in the top menu.
o	Choose "MySQL Community Edition" and select "MySQL Community Server".
	Select Your Operating System:
o	Choose the appropriate version for your operating system (Windows, macOS, Linux).
	Download the Installer: Click on the download link for the installer package.
Step 2: Install MySQL
	Run the Installer: Open the downloaded installer file.
	Choose Setup Type:
o	Windows: Select "Developer Default", "Server only", "Client only", or "Full" setup type as per your needs.
o	macOS/Linux: Follow the package manager instructions if using Homebrew (macOS) or APT/YUM (Linux).
	Follow the Installation Steps:
o	Accept the license agreement.
o	Choose the installation directory if prompted.
o	Configure MySQL server options (e.g., root password, default user).
Step 3: Configure MySQL Server
	Set Up Root Password: During installation, you will be prompted to set a root password. Make sure to remember this password.
	Create User Accounts: Optionally, you can create additional user accounts with different privileges.
Step 4: Start MySQL Server
	Windows:
o	MySQL server will start automatically after installation.
o	Use MySQL Workbench or Command Line to manage the server.
	macOS/Linux:
o	Start the server using the command: sudo mysql.server start.
o	Check the server status using: sudo mysql.server status.
Step 5: Verify Installation
	Open Command Line Interface:
o	Use Command Prompt or PowerShell on Windows.
o	Use Terminal on macOS/Linux.
	Log Into MySQL:
o	Type mysql -u root -p and press Enter.
o	Enter the root password set during installation.
	Check MySQL Version: Type SELECT VERSION(); and press Enter.
Optional: Install MySQL Workbench
	Download MySQL Workbench: Available in the MySQL Community Downloads section.
	Install and Launch MySQL Workbench:
o	Follow the installation instructions specific to your operating system.
o	Use Workbench to manage databases visually.
![alt text](<mySql workbench.png>) ![alt text](<my Sql workbench.png>) ![alt text](<my Sql command 2.png>) ![alt text](<Sql command.png>) ![alt text](<mySql install e.png>) ![alt text](<my Sql install 2.png>) ![alt text](<mySql install.png>)


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Setting Up a Virtual Environment
	Install virtualenv: pip install virtualenv
	Create a Virtual Environment:
o	virtualenv myenv (Windows)
	Activate the Virtual Environment:
o	myenv\Scripts\activate (Windows)

Installing an IDE
	Choose an IDE: Download and install options like PyCharm, Visual Studio Code, or Jupyter Notebook.
	Configure the Python Interpreter: Follow the IDE's instructions to set Python as the interpreter.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Step 1: Identify Your Text Editor or IDE
Choose the text editor or IDE you are using, such as Visual Studio Code (VS Code), PyCharm, Sublime Text, or Atom.
Step 2: Access the Extension/Plugin/Add-on Marketplace
	Visual Studio Code:
o	Open VS Code.
o	Click on the Extensions icon on the sidebar or press Ctrl+Shift+X to open the Extensions view.
	PyCharm:
o	Open PyCharm.
o	Go to File > Settings (or Preferences on macOS) > Plugins.
	Sublime Text:
o	Install Package Control if not already installed.
o	Use Cmd+Shift+P (macOS) or Ctrl+Shift+P (Windows/Linux) and type Install Package.
	Atom:
o	Open Atom.
o	Go to Edit > Preferences (or Atom > Preferences on macOS) > Install.
Step 3: Explore and Install Extensions/Plugins/Add-ons
	Syntax Highlighting:
o	Look for language-specific extensions, e.g., Python, JavaScript.
o	Examples: Python for VS Code, Babel for Atom.
	Linting:
o	Enhances code quality by highlighting errors and potential issues.
o	Examples: ESLint for JavaScript, Pylint for Python.
	Code Formatting:
o	Automatically formats code to maintain consistency.
o	Examples: Prettier for JavaScript, Black for Python.
	Version Control Integration:
o	Integrates Git or other version control systems directly into the editor.
o	Examples: GitLens for VS Code, Git Integration for PyCharm.
Step 4: Configure and Customize Extensions/Plugins/Add-ons
	Access Settings:
o	Each extension/plugin/add-on typically has its own settings accessible through the editor's settings/preferences menu.
	Customization:
o	Adjust settings according to your workflow preferences, such as defining coding standards for linters or customizing key bindings.
Step 5: Keep Extensions/Plugins/Add-ons Updated
	Check for Updates Regularly:
o	Ensure you are using the latest versions to benefit from new features and bug fixes.
o	Most editors have an update mechanism within the extensions/plugins/add-ons manager.



9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    Please check document name: Answers A1

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
