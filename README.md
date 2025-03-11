 # VIRTUAL MACHINE CREATION IN LINUX

## REG NUMBER: 212223040105
## NAME: LOKESHVARAN S
  ## AIM
       To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
Manually executing basic Linux tasks like file management, navigation, and arithmetic operations can be inefficient. This experiment aims to automate these tasks using Bash scripting, including:

Displaying the current directory, files, and system date.
Reading and displaying file contents.
Performing basic arithmetic operations.   
# REQUIREMENTS
Oracle VM VirtualBox Manager
Kali Linux
Mousepad (Text Editor)
Terminal


## ALGORITHM
 ### Steps 1:
 ### Steps 2:
 ### Steps 3:
 ### Steps 4:
 ### Steps 5:
## COMMANDS

# Execute Basic Linux Commands in the Terminal
Check the Current Working Directory
```
pwd
```
Create a New Directory
```
mkdir my_experiment
```
Navigate into the Directory
```
cd my_experiment
```
List the Files in the Directory
```
ls
```

Write Some Text into the File
```
echo "Hello, this is a test file." > myfile.txt
```
Read the File Contents
```
cat myfile.txt
```
Get the Current Date and Time
```
date
```
Writing a Bash Script in Mousepad
Open Mousepad
```
mousepad myscript.sh &
```
Write the Bash Script
```
#!/bin/bash 

echo "Current Directory:"
pwd

echo "Files in this directory:"
ls

echo "Current Date and Time:"
date

read -p "Enter first number: " num1
read -p "Enter second number: " num2

sum=$((num1 + num2))
diff=$((num1 - num2))
prod=$((num1 * num2))
quot=$((num1 / num2))
rem=$((num1 % num2))

echo "Sum: $sum"
echo "Difference: $diff"
echo "Product: $prod"
echo "Quotient: $quot"
echo "Remainder: $rem"

```
Make the Script Executable
```
chmod +x myscript.sh
```
Run the Script
```
./myscript.sh
```
## OUTPUT
Configuration of Kali Linux on Oracle Virtual Box :
![421260654-7481ebf5-8edd-4cb2-87cc-e8e64ec9cafc](https://github.com/user-attachments/assets/489eaf18-f3be-4a42-bfb8-ccee51a27ade)
Output :
![421258284-cc481926-bcfc-4901-b74d-7f5c76beabd5](https://github.com/user-attachments/assets/300ce28c-efa5-4705-922a-e62dd4af6af8)

![421258755-ddc08a53-e155-4a5c-afa4-d4a9429696d3](https://github.com/user-attachments/assets/0225596e-8411-4f64-bf64-65f4657fdaec)
![421262652-a30e5d51-d55c-4ea1-8a39-6bc60e80b50b](https://github.com/user-attachments/assets/c492238e-c185-42ee-99aa-3454e4340338)


 Include your Screenshots Here.
## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.


 

  


