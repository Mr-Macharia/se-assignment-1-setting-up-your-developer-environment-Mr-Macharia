[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15279633&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   - My operating system is Windows 10.
   - First, I checked that my laptop met the system requirements.
   - I downloaded the Media Creation Tool from Microsoft and used it to create a bootable USB drive with the Windows 10 installation files. 
   - Before getting started, I made sure to back up all my important documents, photos, music and other files to an external hard drive, just in case.
   - Then I restarted my laptop and booted from the USB drive. I had to go into the BIOS and change the boot order to make that work. 
   - The Windows 10 setup screen came up and I selected my preferences like my language and region.
   - The setup requested for a product key which I used one of the product keys available on Google.
   - Then I just had to click through and accept the license terms.
   - The actual installation process took a little while - probably 45 minutes or so. It restarted a few times automatically. I just had to wait patiently and not interrupt it.
   - I installed all the latest Windows updates, along with drivers for my hardware like graphics, networking, etc. That helped get everything working smoothly.

   --------------------

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   - The first step was to download the VSCode installer from the official website (https://code.visualstudio.com/). I clicked on the "Download for Windows" button, which prompted the download of an executable file.
   - Once the download was complete, I double-clicked on the installer to begin the installation process. A setup window appeared, and I clicked "Next" to proceed. The installer gave me the option to choose the location where I wanted to install VSCode. I left the default location as is and continued.
   - The next screen presented me with a few optional components to include in the installation, such as adding Open with Code context menu entry, creating a Desktop icon, and adding Open with Code editor entries to the Windows Explorer file context menu. I opted to include all of these components for convenience.
   -  I clicked Next again, and the installation process began. It took a minute or two for the installer to complete its work and I clicked Finish.
   - Before I could start coding, I wanted to customize the editor to suit my preferences. I navigated to the "File" menu and clicked on "Preferences" > "Settings." This opened the Settings editor, where I could configure various aspects of VSCode's behavior, such as theme, font, and keyboard shortcuts.
   - I started by changing the theme to a darker one. I clicked on "Color Theme" in the left-hand sidebar and browsed through the available options. After trying out a few, I settled on the Dracula theme, which had a sleek and modern look.
   - I wanted to enhance my experience by installing some extensions. VSCode has a vast ecosystem of extensions that add new features, language support, and tools to the editor. I opened the Extensions and chose a few that seemed to be resourceful such as blackbox ai and live server.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   - The first step in my Git installation journey was to visit the official Git website (https://git-scm.com/). The website greeted me with a clean and straightforward interface, making it easy to navigate. I clicked on the "Downloads" link, which took me to a page displaying the available downloads for different operating systems.
   - An installation wizard appeared, and I clicked Next to proceed. The next screen presented me with the Git license agreement, which I carefully read and accepted by selecting the "Next" button.
   - After selecting the desired components, I clicked Next and was prompted to choose the default editor for Git. Since I had already installed VSCode I went forward with it.
   - The next screen allowed me to configure additional options, such as enabling file system caching and enabling symbolic links. Since I was just starting with Git, I left the default settings as they were and clicked Next.
   - Once the installation was finished, the installer presented me with the option to launch the Git Bash command-line tool immediately. I checked the box to launch Git Bash and clicked Finish.
   - Before I could start using Git, I needed to configure some basic settings. I began by setting my user name and email address, which would be associated with my commits.
   - With the basic configuration completed, I was ready to start using Git for version control. I created a new directory on my desktop and initialized a new Git repository within it using the mkdir command.
   - I created a simple notebook file, made a commit and pushed it to my github and after the test I was satisfied with the bash.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

   - The first step in my Python installation journey was to visit the official Python website (https://www.python.org/). The website greeted me with a clean and straightforward interface, making it easy to navigate. I clicked on the "Downloads" section, which presented me with the available versions of Python.
   - At the time of my installation, the latest stable version was Python 3.9.x, so I decided to download that version. I scrolled down to the "Windows" section and clicked on the appropriate installer link for my system architecture 64-bit.
   - The installer began downloading, and once it was complete, I double-clicked on the executable file to begin the installation process. An installation wizard appeared, and I clicked Next to proceed.
   - The next screen displayed the Python license agreement, which I carefully read and accepted by selecting Terms in the License Agreement" checkbox and clicking Next.
   - The following screen allowed me to customize the installation options. While the default settings were suitable for most use cases, I wanted to ensure that Python was added to my system's PATH environment variable. This would allow me to run Python scripts from any directory in the command prompt or terminal. I checked the "Add Python to PATH" option and clicked Install.
   - With Python successfully installed, I opened the command prompt (cmd.exe) to verify the installation. I typed python --version. The command prompt displayed the version of Python I had just installed, confirming that the installation was successful and that Python was properly added to my system's PATH.
   - Since I had already installed Visual Studio Code , I decided to use it as my Python IDE. I launched VSCode and navigated to the Extensions view by clicking on the square icon in the sidebar. In the search bar, I typed Python and installed the official Python extension provided by Microsoft.
   - Once the extension was installed, I created a new Python file by clicking on "File" > "New File" and saving it with a ".py" extension. As I started typing Python code in the editor, I immediately noticed the benefits of the Python extension, such as syntax highlighting, code completion, and inline documentation.
   - The file worked well as I typed print("Hello, World!") there was an output on the terminal therefore my installation was done.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   - I had already set up pip during my Python installation process, but I wanted to ensure that it was up-to-date. So, I opened the command prompt and ran python -m pip install --upgrade pip.
   - With pip ready, I decided to install a popular Python library called "requests," which simplifies making HTTP requests in Python. I ran pip install requests.
   - I visited the official Dart website (https://dart.dev/) and navigated to the "Get Dart" section. There, I found instructions for installing Dart on Windows. I had to install chocolatey to my powershell and eventually was able to use chocolatey to install dart. After Dart was installed I added Dart to my path environment. After the installation was complete, I opened a new command prompt and typed dart --version to verify the Dart installation. The command prompt displayed the installed version of Dart, confirming that the setup was successful.
   - I visited the official Flutter website (https://flutter.dev/) and followed the instructions for installing Flutter on Windows. The process involved downloading the Flutter SDK, extracting it to a suitable location, and configuring the system environment variables to include the Flutter bin directory. Once the installation was complete, I opened a new command prompt and ran flutter --version to verify the Flutter installation. The command prompt displayed the installed version of Flutter, confirming that the setup was successful.
   - I opened a new command prompt and used pip to install Django by typing pip install django. To check on whether Django is installed I ran django-admin --version. The output confirmed that I downloaded Django into my system.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   - The first step in my MySQL installation journey was to visit the official MySQL website (https://dev.mysql.com/downloads/). The website greeted me with a clean and user-friendly interface, making it easy to navigate. I clicked on the "Downloads" section, which presented me with the available versions of MySQL for different operating systems.
   - Under the "Windows" section, I found the appropriate installer for the latest stable version of MySQL. I carefully read the release notes and system requirements to ensure compatibility with my Windows machine. Once I was confident about the version, I clicked on the download link, and the installer began downloading.
   - After the download was complete, I double-clicked on the installer executable to begin the installation process. An installation wizard appeared, and I clicked Next to proceed. The next screen displayed the licensing information, which I carefully read and accepted by selecting the appropriate checkbox and clicking Next.
   - The following screen allowed me to choose the setup type. As a beginner, I opted for the "Developer Default" setup type, which includes the essential components required for development and testing purposes.
   - I also chose to configure the MySQL root account password, as this account has full administrative privileges over the database system.
   - With the necessary configurations in place, I reviewed the installation details one last time and clicked Execute to begin the installation process. The installer displayed a progress bar, keeping me informed about the status of the installation.
   - After completing the configuration wizard, the installer informed me that MySQL had been successfully installed and configured on my machine. I clicked Finish to exit the installer.
   - I downloaded and installed MySQL Workbench from the official website, following the step-by-step instructions provided. After the installation was complete, I launched MySQL Workbench and connected it to my local MySQL server instance using the root account credentials.
   - One particularly useful resource I discovered was the official MySQL Documentation (https://dev.mysql.com/doc/). This comprehensive documentation provided detailed explanations, tutorials, and reference materials for MySQL's features, SQL syntax, and best practices.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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
