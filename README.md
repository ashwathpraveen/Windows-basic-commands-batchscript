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

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="606" height="223" alt="image" src="https://github.com/user-attachments/assets/7cda42b9-90c8-4f54-a4b7-7ec014c6a79a" />



Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="842" height="371" alt="image" src="https://github.com/user-attachments/assets/11be3f9e-dfa2-4a06-a2b8-c4e27957782d" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="828" height="352" alt="image" src="https://github.com/user-attachments/assets/da6f3294-454f-4939-9a09-beed47ac582b" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="892" height="143" alt="image" src="https://github.com/user-attachments/assets/283c6bfb-b63d-42b3-9345-fa2d30aa39b7" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="782" height="221" alt="image" src="https://github.com/user-attachments/assets/2e1089da-84a0-4538-96eb-2ccfafd542ed" />




List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="757" height="1059" alt="image" src="https://github.com/user-attachments/assets/0ac343d6-fae4-4ed7-be46-ffe34077bfd7" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="863" height="1106" alt="image" src="https://github.com/user-attachments/assets/fa119743-bfc9-4568-99a8-ef1d71be8755" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="826" height="188" alt="image" src="https://github.com/user-attachments/assets/db0cc345-7b6d-4c2d-a769-13f7f35d7aaf" />




## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="697" height="89" alt="image" src="https://github.com/user-attachments/assets/bde11c07-f7cf-41e4-8dc8-6cd393ff08b9" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="693" height="260" alt="image" src="https://github.com/user-attachments/assets/9c989b2f-9955-4ba3-9783-7ca1ec444bc5" />





Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="715" height="209" alt="image" src="https://github.com/user-attachments/assets/b8c9f229-7df6-4352-90e4-1dbc5437d485" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="696" height="111" alt="image" src="https://github.com/user-attachments/assets/935809fc-35f2-4e68-b5e3-37d738f0ca26" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="753" height="442" alt="image" src="https://github.com/user-attachments/assets/c1c6ddea-849c-4ed9-8aa2-7c171b3f952f" />




# RESULT:
The commands/batch files are executed successfully.

