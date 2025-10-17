# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![image](https://github.com/user-attachments/assets/7799387e-4894-4a75-a2bc-86400584938a)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![image](https://github.com/user-attachments/assets/603d0613-2b4f-4187-bcdc-c80a629edc18)

![image](https://github.com/user-attachments/assets/250bd4ac-ddcf-4628-a58e-7f6d405274fd)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/user-attachments/assets/ea175d8a-d7a2-4f82-93c6-d0ba473945cc)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![image](https://github.com/user-attachments/assets/f9ab3537-1f03-48c1-bdfa-f1dd044bd1b7)

![image](https://github.com/user-attachments/assets/182e0e1c-dc7e-43f4-b440-88025bddbfdd)


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/b358ada1-8d21-486a-9dba-6fb123488c6c)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!






## OUTPUT

![image](https://github.com/user-attachments/assets/cf9a4a04-d8d4-4ef7-8f06-2de1a347f830)




# RESULT:
The commands/batch files are executed successfully.
