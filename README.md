# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\MyLab
```
<img width="707" height="51" alt="328949593-2d4f79b9-b78b-4f2c-bf06-095af7642d40" src="https://github.com/user-attachments/assets/231a5182-6dfa-4f76-b3df-102560be8e0b" />

## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
```
<img width="650" height="106" alt="328949673-bbadcf18-2ce4-4c5d-a2b9-567e61f9c906" src="https://github.com/user-attachments/assets/f8311e8a-97e1-4fb9-923c-c3ea7b22ec5a" />

```
type nul > MyFile.txt
```

<img width="698" height="101" alt="328949736-6754bdb8-cd39-4007-8dbc-52a8dfb616de" src="https://github.com/user-attachments/assets/8178985e-874a-4473-9ef6-f7f337ebcc0f" />

## COMMAND AND OUTPUT
```
dir %userprofile%\Desktop\MyLab
```

<img width="815" height="321" alt="328949803-54a3204d-1415-409f-9498-a55cdf34b56d" src="https://github.com/user-attachments/assets/6f56a38b-d33e-4cba-8afb-bd0feb593c21" />


## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```

<img width="800" height="102" alt="328949863-63b4bec5-7694-456f-9745-ebeef64af7d9" src="https://github.com/user-attachments/assets/a5ef4c30-4a07-4544-8b80-ce6f8d3b5db6" />


## COMMAND AND OUTPUT
```
copy MyFile.txt %userprofile%\Desktop\Backup
```
<img width="925" height="143" alt="328949949-c1cce673-92e2-4e4b-b8e8-bb73c553479a" src="https://github.com/user-attachments/assets/8ace7a32-f604-42dd-ad41-81d7d63ff16f" />


## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Documents

move MyLab Documents
```

<img width="853" height="132" alt="328950015-d617b586-645a-4c52-837f-d8a6b0a1d0a8" src="https://github.com/user-attachments/assets/c4fcab81-24cb-46b3-9ebb-252471c78d11" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```


## OUTPUT

<img width="957" height="247" alt="328950083-5b056a85-f3c1-4139-8603-8eba276d227c" src="https://github.com/user-attachments/assets/4289cb62-1025-44e0-a3cc-8ae68ee46c94" />


## command
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

<img width="891" height="223" alt="328950144-784daff7-4c23-494d-bd68-a98bd055c0cf" src="https://github.com/user-attachments/assets/c2f37fa8-33f9-4c06-abb0-e24d80402519" />


# RESULT:
The commands/batch files are executed successfully.

