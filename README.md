# Remote acces trojan


## Description
This is a malware development. It is written in the C programming language and showcases various features commonly found in malware. It is important to note that this project is intended for educational purposes only, and its use for any malicious activities is strictly prohibited.

## Features
The malware project includes the following features:

### Persistence
The malware achieves persistence on the infected system by adding a registry key to the "Run" section. This ensures that the malware is executed every time the user logs on to the system.

### Keylogger
A keylogger functionality is implemented in the malware, which captures keyboard inputs. It monitors various keys, including alphabets, numbers, special characters, and function keys, and saves the captured keys to a file named "windows.txt". This feature demonstrates the potential threat of keyloggers and the importance of securing sensitive information.

### Remote Command Execution
The malware acts as a backdoor, allowing remote control of the infected system. It listens for commands from a remote server and executes them on the compromised machine. The commands can include actions such as changing directories, enabling persistence, starting the keylogger, and executing shell commands.

## Prerequisites
To run the malware, the following prerequisites are necessary:
- Windows operating system (tested on Windows 10)
- kali linux for the server side to listen and execute command

## Installation
To install and run the malware, follow these steps:
1. save the file to an .exe file 
 

## Usage
To utilize the malware's features, perform the following steps:
1. Set up a remote server to communicate with the infected machines.
2. Compile and run the server code on your machine.
3. Modify the server code to set the appropriate IP address and port that matches your remote server configuration.
4. Start the server, which will listen for incoming connections from the infected machines.
5. Once a connection is established, the server will prompt you to enter commands.
6. Enter commands to control the infected machines. Available commands include:
   - `q`: Close the connection and exit the server.
   - `cd <directory>`: Change the current working directory on the infected system.
   - `persist`: Enable persistence by adding a registry key for the malware to run on system startup.
   - `keylog_start`: Start the keylogger functionality on the infected machine.
7. The server will send the commands to the infected machines and display the responses received from them.

**Please exercise extreme caution when running this code. It is essential to use this code responsibly and solely for educational purposes. Unauthorized access or unauthorized use of computer systems is illegal and unethical. The project authors and contributors do not endorse or support any malicious activities.**

## Contribution
Contributions to this project are not accepted. This project is intended for personal learning and educational purposes only. However, you are welcome to fork the repository and use the code as a reference for your own educational endeavors.



