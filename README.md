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
<img width="961" height="187" alt="560071685-92d84061-6cd6-47a8-9686-c0b198666399" src="https://github.com/user-attachments/assets/8c20ba56-6715-4dea-9201-e9d8f1a7c291" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="930" height="250" alt="560071738-691c756f-e12b-4edb-81f7-570ca9287f12" src="https://github.com/user-attachments/assets/61c94a21-9aeb-448a-ae5f-74c1fb5df434" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="858" height="217" alt="560071811-9e41810f-ec9a-41aa-bcd7-48e4a5028f38" src="https://github.com/user-attachments/assets/5e00157f-c03a-45e8-b028-9a099d2d1de6" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1055" height="111" alt="560071950-9b6547b5-ed8d-432e-ac93-3bff8c935108" src="https://github.com/user-attachments/assets/188ebd8c-2f0e-481c-afe1-3ebcdc5ff489" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="992" height="139" alt="560072102-9a96b2ef-b400-4133-b272-4f9cd10d05c4" src="https://github.com/user-attachments/assets/7e1a3072-edcf-4384-ac26-c442675e2799" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="1055" height="111" alt="560073195-94b80332-e1bd-4e12-b13b-bc2aab64b4e8" src="https://github.com/user-attachments/assets/ada339d4-5d53-4e1f-a2e5-8c0302d833ef" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="876" height="236" alt="560073157-5ccafe25-4bb9-4442-a310-01e7cb51d76e" src="https://github.com/user-attachments/assets/ba18084f-f670-49f2-a2c4-b8fbdb3586d8" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="638" height="867" alt="560072830-ae28dd6d-b491-488c-afd8-b5029d31a20e" src="https://github.com/user-attachments/assets/3cc5b8f9-886d-48d5-a81e-4ae644ea0798" />


Compare the file hello.txt and rose.txt
<img width="872" height="200" alt="560072207-d59af770-e2c4-4192-b3c0-8fbbf791f6fd" src="https://github.com/user-attachments/assets/f283477f-f799-434d-b629-bd7144e7f5a0" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="882" height="106" alt="560072291-addffa64-b1a6-4b6a-81ce-705d4842bc1c" src="https://github.com/user-attachments/assets/c08b39fe-3a1d-4e4c-9760-f953b388c709" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="888" height="267" alt="560072552-4085fe46-3b9d-42e9-a1ed-810a3c7ec3ff" src="https://github.com/user-attachments/assets/cb964565-84b0-47f6-8c67-e3f021bdd983" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="883" height="201" alt="560072599-69d57188-da52-40b1-aeb1-775e0c8bd215" src="https://github.com/user-attachments/assets/3d83bc98-79eb-450d-8320-9f884416e15d" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="853" height="89" alt="560072672-c5a3caf4-3a35-41b2-9127-e3c4648c399e" src="https://github.com/user-attachments/assets/b420379e-614d-4578-ba0f-d6a43a4fc72d" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="829" height="404" alt="560072700-69d8acf1-32b6-4c88-9a8e-7c001fa9f96b" src="https://github.com/user-attachments/assets/9fcb4137-e5a8-416a-ac3a-b467e24d56b2" />



# RESULT:
The commands/batch files are executed successfully.

