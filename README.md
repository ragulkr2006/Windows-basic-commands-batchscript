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

<img width="460" height="104" alt="image" src="https://github.com/user-attachments/assets/8d63453b-e652-43e1-a0b8-84858109679a" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="773" height="191" alt="image" src="https://github.com/user-attachments/assets/35dd7dfc-f677-4552-9bd1-2a1d6673fdf3" />

## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="669" height="430" alt="image" src="https://github.com/user-attachments/assets/510e27ac-3026-475f-9e2a-e5d375202443" />

## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="676" height="178" alt="image" src="https://github.com/user-attachments/assets/83b1e5fb-4ddf-42d5-a5c5-392e6a5bbd34" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="641" height="112" alt="image" src="https://github.com/user-attachments/assets/1721dbbd-5a69-4932-b71e-8218248562b4" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="672" height="108" alt="image" src="https://github.com/user-attachments/assets/048a50bd-f267-4c7c-a58c-efb6a596b7ea" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="670" height="109" alt="image" src="https://github.com/user-attachments/assets/0eb7994f-da7c-4ebc-be57-f6f478786781" />

## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="672" height="762" alt="image" src="https://github.com/user-attachments/assets/9665b805-7169-4b50-8e9c-5945a09d4bd6" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="674" height="769" alt="image" src="https://github.com/user-attachments/assets/b4edd546-3250-43d9-a8b1-deba99c69105" />


## COMMAND AND OUTPUT

<img width="669" height="255" alt="image" src="https://github.com/user-attachments/assets/419adb8c-0861-444e-9157-eef84e65428d" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="673" height="184" alt="image" src="https://github.com/user-attachments/assets/affd3d7e-6e19-4897-8249-c3e4a1ebc93e" />


## OUTPUT

<img width="676" height="190" alt="image" src="https://github.com/user-attachments/assets/6d060458-f2c1-4ca1-bf5f-edbd382b93f0" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="671" height="233" alt="image" src="https://github.com/user-attachments/assets/c849d226-3768-44be-b925-2c764c47dda9" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="664" height="252" alt="image" src="https://github.com/user-attachments/assets/e4085516-ef2a-44d1-9d3a-b4c5ffdc3ddd" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


<img width="672" height="192" alt="image" src="https://github.com/user-attachments/assets/68f6957b-b58d-4714-97f7-d1b966af89ed" />



# RESULT:
The commands/batch files are executed successfully.

