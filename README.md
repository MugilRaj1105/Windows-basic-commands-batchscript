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
mkdir %userprofile%\Desktop\MyLab

![image](https://github.com/MugilRaj1105/Windows-basic-commands-batchscript/assets/154905390/35221a08-e9cd-45b4-b44e-d90a9a1a808c)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/MugilRaj1105/Windows-basic-commands-batchscript/assets/154905390/90c5fa38-78c6-4346-8c90-dc7f196b9421)
![image](https://github.com/MugilRaj1105/Windows-basic-commands-batchscript/assets/154905390/b95f2ffe-811b-4172-87ef-4cacc1fe737d)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/MugilRaj1105/Windows-basic-commands-batchscript/assets/154905390/f36486b2-e1fb-4000-a718-e900b560ff9b)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![image](https://github.com/MugilRaj1105/Windows-basic-commands-batchscript/assets/154905390/b916992a-a155-4fb5-a4f9-b56f8f1e2861)
![image](https://github.com/MugilRaj1105/Windows-basic-commands-batchscript/assets/154905390/e640a77f-95f9-4610-bd47-cdf9bc15dace)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/MugilRaj1105/Windows-basic-commands-batchscript/assets/154905390/43595b78-99bf-4e6f-9a99-93418c895b21)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT
![image](https://github.com/MugilRaj1105/Windows-basic-commands-batchscript/assets/154905390/ea459537-6c96-4df4-989d-632966d3ea26)

## RESULT:

The commands/batch files are executed successfully.






