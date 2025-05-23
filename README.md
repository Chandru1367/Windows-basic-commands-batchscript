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

![image](https://github.com/user-attachments/assets/e1aab195-4fcc-4ed9-b238-d2979e5e7794)


## COMMAND AND OUTPUT

Remove the directory "my-folder"

![image](https://github.com/user-attachments/assets/c3c4b801-8af0-47fc-818f-3741ab1df5f9)


## COMMAND AND OUTPUT


Create the file Rose.txt

![image](https://github.com/user-attachments/assets/95a2301c-ce78-46bf-95fc-220709b95d30)


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

![image](https://github.com/user-attachments/assets/1001bd3a-ea1c-41eb-abae-df80364006b4)


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

![image](https://github.com/user-attachments/assets/a733bf62-dd25-48f7-bc95-1ad4fbb856ed)


## COMMAND AND OUTPUT

Remove the file hello1.txt

![image](https://github.com/user-attachments/assets/1a8a46af-b8c9-4392-90c2-ac0fc5d2e4a4)



## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

![image](https://github.com/user-attachments/assets/680b7b10-996f-4b99-92c4-dd670076c4cb)


## COMMAND AND OUTPUT

List out all the associated file extensions 

![image](https://github.com/user-attachments/assets/69cb9a9b-442e-455a-96c9-d7882f8b833c)


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

![image](https://github.com/user-attachments/assets/063452ca-d687-45e0-98b9-09b9fe4b1d47)


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

![image](https://github.com/user-attachments/assets/b4fee408-cfba-420b-950b-52c0c8bf1053)


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT

![image](https://github.com/user-attachments/assets/3e7c1d70-b94a-4f3c-8636-7a7331875cbe)



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

![image](https://github.com/user-attachments/assets/c15114ef-dc94-4a2c-b94a-293cde1a92d1)



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

![image](https://github.com/user-attachments/assets/c36c76cc-58bb-4c6a-8744-9710a829798c)


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

![image](https://github.com/user-attachments/assets/d82b57e4-8250-4ffb-993c-bd2010ec760a)



# RESULT:
The commands/batch files are executed successfully.

