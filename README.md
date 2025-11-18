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
## COMMAND AND OUTPUT
Create a directory named "my-folder"
```
 mkdir %userprofile%\Desktop\Varshini
```
<img width="760" height="318" alt="Screenshot 2025-11-16 211403" src="https://github.com/user-attachments/assets/25060bd8-722d-493a-bfe1-0b9539bdf986" />

```
 cd %userprofile%\Desktop\Varshini
```
<img width="712" height="79" alt="Screenshot 2025-11-16 211615" src="https://github.com/user-attachments/assets/90ac79f4-c7c1-449b-9d37-050e07a22d48" />

Remove the directory "my-folder"
```
 rmdir Varshini
```
<img width="701" height="80" alt="Screenshot 2025-11-16 211654" src="https://github.com/user-attachments/assets/4b2c0f74-0882-4730-8969-b7da1c005801" />



Create the file Rose.txt
```
type nul > rose.txt
```
<img width="581" height="113" alt="Screenshot 2025-11-16 211807" src="https://github.com/user-attachments/assets/2917eadc-c6c8-4c6a-911b-d74886f30125" />



Create the file hello.txt using echo and redirection
```
echo Hello World > hello.txt
```
<img width="577" height="106" alt="Screenshot 2025-11-16 211820" src="https://github.com/user-attachments/assets/1f72bf35-c8a3-4ba0-ab7f-2c14932f5cc5" />


Copy the file hello.txt into the file hello1.txt
```
copy hello.txt hello1.txt
```
<img width="613" height="123" alt="Screenshot 2025-11-16 211832" src="https://github.com/user-attachments/assets/7eb64f8e-bb94-47f7-bee5-db1901e87e88" />

Remove the file hello1.txt
```
del hello1.txt
```
<img width="600" height="110" alt="Screenshot 2025-11-16 211842" src="https://github.com/user-attachments/assets/c05ce7ee-31ed-4754-a179-37b476cb9d79" />


List out the file hello1.txt in the current directory
```
dir
```


List out all the associated file extensions 
```
assoc
```



Compare the file hello.txt and rose.txt
```
fc hello.txt rose.txt
```
<img width="621" height="223" alt="Screenshot 2025-11-16 212012" src="https://github.com/user-attachments/assets/4c18d937-438d-4bad-a7ba-21d7d11503ef" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT


<img width="501" height="90" alt="Screenshot 2025-11-16 212623" src="https://github.com/user-attachments/assets/8f9faeae-3b2b-4ae6-8e06-576044fe6595" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="614" height="271" alt="Screenshot 2025-11-16 213040" src="https://github.com/user-attachments/assets/a8b81bb1-9ce5-4797-9b95-2877b6a94ee1" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="402" height="229" alt="Screenshot 2025-11-16 213206" src="https://github.com/user-attachments/assets/3584cc4d-66bd-40e3-b05d-ed7513beaca2" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="421" height="93" alt="Screenshot 2025-11-16 213524" src="https://github.com/user-attachments/assets/fa215507-6545-49fa-943c-8ea135bbfcc1" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="462" height="486" alt="Screenshot 2025-11-16 213631" src="https://github.com/user-attachments/assets/d18b1306-d923-47e2-8a86-cb99323faa5e" />


# RESULT:
The commands/batch files are executed successfully.

