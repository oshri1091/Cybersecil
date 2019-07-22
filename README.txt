The following Application was written by Oshri Rabani, https://Cybersecil.com.
For inquiries and questions, please contact: info@cybersecil.com
___________________________________________________________________________________________________________________________________________________________________________________________

The following Application allows you to back up your systems quickly, easily and easily.
Steps:

1. Choose how you want to backup your systems. 
   One option is to upload a CSV file containing your list of systems (including system type, SSH port, user name and password). A second option is to choose "Standard" - this method will require you to upload a TXT file, which lists your systems, and enter the authentication method for your systems.

2.1. option 1 - "Upload CSV":
2.1.1. Prepare a CSV file with the list of IP addresses of your systems (a template for creating a CSV file in ZIP - "IP Example.csv list").
2.1.2 Activate the software.
2.1.3 Select the folder to which you want to export your configuration files and click OK to continue.
2.1.4 If the file is correct, you will be asked to choose between the "Run Commands" option that will allow you to run commands on your systems or "Backup" to back up your systems.
2.1.4.1 If you select "Run Commands" enter the commands you want to run on the systems and press "GO", otherwise skip to the next step.
2.1.5 You will now see a list of the systems you have selected. If the information is correct, press GO to launch the application.

2.2. Option 2 - Standard:
2.2.1. Prepare a text file with a list of IP addresses of your systems (load a list of systems of the same type, such as Fortigate List, List for HP Switch, etc.).
2.2.2. Start the software.
2.2.3. Select the type of equipment you want to back up.
2.2.4. Select the location of the file that lists the system IP addresses.
2.2.5. Enter the port number to connect to the SSH (default 22)
2.2.6. Enter your username
2.2.7. Enter the password
2.2.8. Select the folder to which you want to export your configuration files.
2.2.9. Now, press "SUBMIT" to continue.
2.2.10 If the file is correct, you will be asked to choose between the "Run Commands" option that will allow you to run commands on your systems or "Backup" to back up your systems.
2.2.10.1 If you select "Run Commands" enter the commands you want to run on the systems and press "GO", otherwise skip to the next step.
2.2.11 You will now see a list of the systems you selected. If the information is correct, press GO to launch the application.

___________________________________________________________________________________________________________________________________________________________________________________________

Remarks:
* If you want to back up a number of different systems or systems with different identifiers - select "Upload CSV" or select "STANDARD".
* Running commands is possible on a list of systems of the same type only.
* The system only supports Secure Access (SSH).
* Fortigate systems - The system connects to SSH and runs the following command that allows access to SCP (file transfer in SSH protocol):
"config system global -> set admin-scp enable -> end." . The application then connects to Fortigate on SCP and copies the configuration file.
* During the running of the software you will be able to see the progress of the operations in your systems.
* After running the software will export the backup files / output of the command run as well as log file of the system.

___________________________________________________________________________________________________________________________________________________________________________________________

All rights reserved to Oshri Rabani and Cybersecil.com !
Use of user responsibility only!

GoodLuck!