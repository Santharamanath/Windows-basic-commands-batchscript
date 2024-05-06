# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting
Name:Santha ramanath M

Register number:212223220097
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
mkdir %userprofile%\Desktop\MyLab

![327992700-528a3189-2594-433f-b9f8-d4f3ff03510a](https://github.com/Santharamanath/Windows-basic-commands-batchscript/assets/149035289/24f42e76-4fa3-4c1a-97a5-b0dcc1ae6e37)


Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
cd %userprofile%\Desktop\MyLab

![327992732-f4261fea-d2ce-4e9f-a081-1d3afeeaf6c0](https://github.com/Santharamanath/Windows-basic-commands-batchscript/assets/149035289/58f8d043-bceb-4c5c-8b47-06bd2d4b2853)

![327992739-add459fe-4274-4007-ae28-86da5f0aa09e](https://github.com/Santharamanath/Windows-basic-commands-batchscript/assets/149035289/dc7f537f-f0c2-4ad3-ba3a-598f892893ac)


List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
dir %userprofile%\Desktop\MyLab

![327992762-d61a108d-87c5-43ec-990e-4c1eccf64faf](https://github.com/Santharamanath/Windows-basic-commands-batchscript/assets/149035289/cfc52320-4e7a-4c0e-ac96-3e3814743699)


Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup

![327992786-453c834a-b6ee-48b5-9472-4ed7877d6c24](https://github.com/Santharamanath/Windows-basic-commands-batchscript/assets/149035289/07518ea1-f4f3-4d84-b68b-c9088cf92e4b)

![327992794-4c545975-081b-4b54-8d3e-e14b66c37930](https://github.com/Santharamanath/Windows-basic-commands-batchscript/assets/149035289/d4d0d957-5106-4ddf-9a8b-cb42fb3937b0)


Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents

![327992815-10c715c8-e70a-454c-aab3-3dffe411996b](https://github.com/Santharamanath/Windows-basic-commands-batchscript/assets/149035289/96a21b58-5130-40e0-b558-6124d5d3649c)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```




## OUTPUT

![327992847-9566484b-09ef-4248-8f21-e18833ab98de](https://github.com/Santharamanath/Windows-basic-commands-batchscript/assets/149035289/36eab9f3-7718-43a5-95f6-a35d4f07aedf)




# RESULT:
The commands/batch files are executed successfully.

