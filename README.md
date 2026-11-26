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
mkdir my-folder
<img width="411" height="39" alt="image" src="https://github.com/user-attachments/assets/5e866b7a-7884-49e2-a382-ab6f316ffe69" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="490" height="104" alt="image" src="https://github.com/user-attachments/assets/41d6d298-ead8-4421-8924-75b6266fc593" />

rmdir my-folder
Create the file Rose.txt

## COMMAND AND OUTPUT
COPY CON Rose.txt A clock in a office can never get stolen Too many employees watch it all the time
<img width="815" height="497" alt="image" src="https://github.com/user-attachments/assets/9e6fed2e-5a29-45cb-b49f-59eb1747fc75" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
echo “hello world” > hello.txt type hello.txt
<img width="498" height="158" alt="image" src="https://github.com/user-attachments/assets/e5153a6c-e1e7-4b93-93ac-35b1cc5b2ff9" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
copy hello.txt hello1.txt type hello1.txt
<img width="528" height="136" alt="image" src="https://github.com/user-attachments/assets/6bb390af-885f-4cf5-9ab5-f584ceb25e33" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
del hello1.txt dir hello1.txt
<img width="461" height="238" alt="image" src="https://github.com/user-attachments/assets/51d11795-e5b0-4366-bfa1-b66b641f28c5" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="551" height="839" alt="image" src="https://github.com/user-attachments/assets/1646ba1e-ea20-4851-b201-05192eac380a" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
fc hello.txt Rose.txt

<img width="557" height="246" alt="image" src="https://github.com/user-attachments/assets/b70210c1-ab48-46e0-b719-25420585679c" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

@echo off set name=John echo Hello, %name%! pause



## OUTPUT

<img width="422" height="134" alt="image" src="https://github.com/user-attachments/assets/05aee551-8530-453b-be9a-53d4d4deccbb" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="601" height="246" alt="image" src="https://github.com/user-attachments/assets/0968b7a1-1e12-468f-aaf9-ce925bf98715" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="409" height="168" alt="image" src="https://github.com/user-attachments/assets/3450de57-0631-4ce7-a258-59a0eaff3211" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="631" height="241" alt="image" src="https://github.com/user-attachments/assets/90b51765-79bf-4c38-bd6a-44a48e4b5e2c" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="496" height="415" alt="image" src="https://github.com/user-attachments/assets/e4734da2-3023-4a5c-816e-4570f3a26fb4" />



# RESULT:
The commands/batch files are executed successfully.

