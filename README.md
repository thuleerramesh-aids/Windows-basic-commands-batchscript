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
<img width="2103" height="748" alt="image" src="https://github.com/user-attachments/assets/63c78d1c-231f-45c5-81ed-d82fda66d900" />



Remove the directory "my-folder"
## COMMAND AND OUTPUT
<img width="645" height="160" alt="Screenshot 2026-08-06 142543" src="https://github.com/user-attachments/assets/dce7b14d-981e-4967-938b-9d948475ab0c" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="1716" height="917" alt="image" src="https://github.com/user-attachments/assets/896af295-94db-40a0-afbf-866d8e74d124" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="649" height="69" alt="Screenshot 2026-08-06 142619" src="https://github.com/user-attachments/assets/768c609e-6ae5-4c13-93bf-e4882cb393c7" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="608" height="71" alt="Screenshot 2026-08-06 142636" src="https://github.com/user-attachments/assets/1efe975e-ec97-41b7-aa02-b5b19d047c01" />


Remove the file hello1.txt and List out the file hello1.txt in the current directory9

## COMMAND AND OUTPUT

<img width="586" height="109" alt="Screenshot 2026-08-06 142646" src="https://github.com/user-attachments/assets/cd69e96b-eab3-4aab-8633-37a7700ab4bc" />



List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="648" height="323" alt="Screenshot 2026-08-06 142658" src="https://github.com/user-attachments/assets/fbc5205a-ff9a-4119-baa5-4ca5b8416534" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="640" height="134" alt="Screenshot 2026-08-06 142716" src="https://github.com/user-attachments/assets/dc6f3fee-6b74-4b3a-88a8-a7c3f9a16416" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="524" height="43" alt="Screenshot 2026-08-06 142730" src="https://github.com/user-attachments/assets/267413d3-8a48-4d56-aaee-9ca1b190209d" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="544" height="138" alt="Screenshot 2026-08-06 142743" src="https://github.com/user-attachments/assets/b9699699-c7d9-47a2-a320-d70a0c0ec4c1" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="526" height="110" alt="Screenshot 2026-08-06 142802" src="https://github.com/user-attachments/assets/c9a99852-685b-4dba-ae2e-052e8937aa97" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="622" height="132" alt="Screenshot 2026-08-06 142819" src="https://github.com/user-attachments/assets/940f40be-71b0-4641-a6ef-c023d586e3ee" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="521" height="234" alt="Screenshot 2026-08-06 142832" src="https://github.com/user-attachments/assets/24941d9e-569f-461b-a9f0-df115d56ab1b" />



# RESULT:
The commands/batch files are executed successfully.
