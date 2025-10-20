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

<img width="607" height="81" alt="Screenshot 2025-10-20 184145" src="https://github.com/user-attachments/assets/30cd0dfc-3988-4e04-8728-6af52957071a" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="627" height="73" alt="Screenshot 2025-10-20 184206" src="https://github.com/user-attachments/assets/2f3e7731-d124-4e9b-a484-df7f8f68979f" />


## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="929" height="389" alt="Screenshot 2025-10-20 184219" src="https://github.com/user-attachments/assets/8cae14f5-5a6d-4105-8749-dc9968217c76" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="868" height="117" alt="Screenshot 2025-10-20 184253" src="https://github.com/user-attachments/assets/def3a9ee-d0a6-48d6-bc6e-f1c9d405b0b6" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="817" height="77" alt="Screenshot 2025-10-20 184310" src="https://github.com/user-attachments/assets/b24d6edd-1a0d-4eb7-b9bc-f79632ce2fa8" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="824" height="60" alt="Screenshot 2025-10-20 184327" src="https://github.com/user-attachments/assets/da2604e7-9998-497d-9b8e-ec11d2e703c1" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="705" height="184" alt="Screenshot 2025-10-20 184346" src="https://github.com/user-attachments/assets/68491044-2882-44a0-acbd-9f9b86fb15cc" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="589" height="1056" alt="Screenshot 2025-10-20 185050" src="https://github.com/user-attachments/assets/b898f675-7fad-49d7-bb26-322f69ebba01" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="708" height="220" alt="Screenshot 2025-10-20 185114" src="https://github.com/user-attachments/assets/da868069-d0b9-4f7d-8ef8-197907bd381f" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting

Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="655" height="154" alt="Screenshot 2025-10-20 192217" src="https://github.com/user-attachments/assets/f4127465-901c-4a3b-bf94-adfceb37fb6c" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT

<img width="696" height="445" alt="Screenshot 2025-10-20 192449" src="https://github.com/user-attachments/assets/1ccdb2b4-a88a-4cd3-9f03-9c1c6eb832d7" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


## OUTPUT

<img width="587" height="254" alt="Screenshot 2025-10-20 192618" src="https://github.com/user-attachments/assets/6fabc69e-0a47-4c41-a8a8-b24feea09c55" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):


## OUTPUT

<img width="680" height="304" alt="Screenshot 2025-10-20 192839" src="https://github.com/user-attachments/assets/e40991b2-afdb-4b32-91c7-38feeec6f3f1" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="904" height="459" alt="Screenshot 2025-10-20 193054" src="https://github.com/user-attachments/assets/ad10d189-8520-46fb-981e-db6473db57f7" />


# RESULT:
The commands/batch files are executed successfully.

