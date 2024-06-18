[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15286382&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   STEPS FOLLOWED;
   WHAT YOU NEED;
   1.USB flash drive with at least 5GB free space,ensure the flash disk has nothing important since it will be formatted.
   2.Technician PC - Windows PC that you'll use to format the USB flash drive
   3.Destination PC - A PC that you'll install Windows on
   
   STEP ONE- Format the drive and set the primary partition as active.
   Connect the USB flash drive to your technician PC.
   Open Disk Management: Right-click on Start and choose Disk Management.
   Format the partition: Right-click the USB drive partition and choose Format. Select the FAT32 file system to be able to boot either BIOS-based or UEFI-based PCs.
   Set the partition as active: Right-click the USB drive partition and click Mark Partition as Active.

   STEP TWO - Copy Windows Setup to the USB flash drive.

   Use File Explorer to copy and paste the entire contents of the Windows product DVD or ISO to the USB flash drive.
   Optional: add an unattend file to automate the installation process. For more information, see Automate Windows Setup.

  STEP THREE - Install Windows to the new PC.

  Connect the USB flash drive to a new PC.
  Turn on the PC and press the key that opens the boot-device selection menu for the computer, such as the Esc/F10/F12 keys. Select the option that boots the PC from the USB flash drive.
  Windows Setup starts. Follow the instructions to install Windows.
  Remove the USB flash drive.

   ![alt text](image.png)

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

  STEP ONE: Download Visual Studio
 Visit the Visual Studio website and click on "Download Visual Studio."
 Follow the on-screen instructions to download the installer.

  STEP TWO:Run the Installer:
Run the downloaded installer.
Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.

  STEP THREE:Select Workloads and Components:
In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development."

  STEP FOUR:Modify Installation (Optional):
If needed, you can customize the installation by clicking on the "Individual components" tab in the installer and selecting or deselecting specific components."

  STEP FIVE:Install:
Click the "Install" button to start the installation process.
This may take some time, as it involves downloading and installing the selected components.

  STEP SIX:Launch Visual Studio:
Once the installation is complete, launch Visual Studio.
Sign in with your Microsoft account or create one if prompted.

  STEP SEVEN:Choose Development Environment:
On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.

  STEP EIGHT:Start Coding:
You're now ready to start coding! Create a new project or open an existing one to begin your development work.
![alt text](image.png)

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

 Download Git:

Visit the Git for Windows website.
Click on the "Download" button to get the latest version.
Install Git:

Run the downloaded installer.
Follow the installation wizard. You can generally accept the default settings, but pay attention to the following options:
Adjusting your PATH environment: Ensure "Git from the command line and also from 3rd-party software" is selected.
Choosing the default editor used by Git: Select your preferred text editor (e.g., Vim, Notepad++, VS Code).
Adjusting the name of the initial branch: Leave it as "master" unless you have a reason to change it.
Configuring the line ending conversions: Choose "Checkout Windows-style, commit Unix-style line endings".

Step 2: Configure Git
After installing Git, you need to configure your user name and email address. This information will be associated with your commits.
 git config --global user.email "name@gmail.com"
 git config --global user.name "Your name"

Step 3: Verify Configuration
To verify that your configuration settings have been applied correctly:

git config --list
This command will display a list of all the configuration settings for Git, including your username and email.

https://github.com/valerian-njoroge/demo-first

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  STEP ONE:Installation on Windows
  Visit https://www.python.org/downloads/to download the latest release of Python
   When we click on the above link, it will bring us the following page.
   ![alt text](image.png)
  
  STEP TWO: Click on the Install Now

Double-click the executable file, which is downloaded;the following window will open.
![alt text](image-1.png)
Select Customize installation and proceed.
Click on the Add Path check box, it will set the Python path automatically.
We can also click on the customize installation to choose desired location and features. Other important thing is install launcher for the all user must be checked.

Step - 3 Installation in Process
![alt text](image-1.png)
Now, try to run python on the command prompt. Type the command python -version in case of python3.

![alt text](image.png)
5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   ![alt text](image.png)

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   STEP ONE:
   Visit https://dev.mysql.com/downloads/windows/installer/5.7.html
   this will pop up on your page
   ![alt text](image.png)
   
  Select and download your preferred version. In this example, we selected the Full MySQL Package (B).

  STEP TWO:After selecting B, you are provided with the option of signing up for a MySQL Community account. If you are not interested, select the No thanks, just start my download option at the bottom of the page.
  ![alt text](image.png)
   
   STEP THREE:By selecting this option, the download process starts immediately. Once the download is complete, you can execute the MySQL Installer file from the download folder.
   It can take a few moments while Windows configures the MySQL Installer and prepares the installation and configuration process.

   STEP FOUR:Set Up MySQL Installer 
   we select the Server Only option and click Next.
   ![alt text](image.png)
   Click Execute to begin the installation process.
   ![alt text](image.png)
   
    Once the status of the installation status is labeled as Complete, you are ready to configure the MySQL database.

    STEP FIVE:Configure MySQL Server
    The MySQL Server 8.0.19 is now ready to be configured. Initiate the process by clicking Next.
    ![alt text](image.png)
   

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
https://github.com/valerian-njoroge/demo-first

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
