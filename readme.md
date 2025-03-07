# Ethernet Communication in Python

This code implements ethernet communication (TCP) with an external device. It is based on the socket library. 

&nbsp;

<div align="center"><img src="docs/preview.gif" width="800"></div>

&nbsp;

## Dependencies

This code uses the following libraries:
- `socket`: For handling system resources
- `pandas`: For creating a list of class instances

&nbsp;

## Usage

In your Python script: 
```
IP = 'Your_IP'
PORT = 23
name = 'Your_name'
ethernet = ethernet(name, IP, PORT)
ethernet.connect()
command = 'Your_command'
response = ethernet.send_and_receive(command)
```

&nbsp;

## How it Works

The app as follows:
1. The class is initialized with the port IP and a name
2. send_and_receive encodes and sends your message using utf-8 byte encoding 
3. the response is decoded automatically

&nbsp;

## Repository Structure
```
repository/
├── ethernet.py # the class is in this python file
├── requirements.txt # the python packages needed to run locally
├── .gitignore # includes the local virtual environment named my_env
└── docs/
    └── preview.png # preview photo for Github
```

&nbsp;

## Topics 
```
Python | Ethernet | Communication
External device | decode bytes | communication | custom classes
Self taught coding | Mechanical engineer | Robotics engineer 
Brian Lesko | Brian Joseph Lesko
```
&nbsp;

<hr>

&nbsp;

<div align="center">



╭━━╮╭━━━┳━━┳━━━┳━╮╱╭╮        ╭╮╱╱╭━━━┳━━━┳╮╭━┳━━━╮
┃╭╮┃┃╭━╮┣┫┣┫╭━╮┃┃╰╮┃┃        ┃┃╱╱┃╭━━┫╭━╮┃┃┃╭┫╭━╮┃
┃╰╯╰┫╰━╯┃┃┃┃┃╱┃┃╭╮╰╯┃        ┃┃╱╱┃╰━━┫╰━━┫╰╯╯┃┃╱┃┃
┃╭━╮┃╭╮╭╯┃┃┃╰━╯┃┃╰╮┃┃        ┃┃╱╭┫╭━━┻━━╮┃╭╮┃┃┃╱┃┃
┃╰━╯┃┃┃╰┳┫┣┫╭━╮┃┃╱┃┃┃        ┃╰━╯┃╰━━┫╰━╯┃┃┃╰┫╰━╯┃
╰━━━┻╯╰━┻━━┻╯╱╰┻╯╱╰━╯        ╰━━━┻━━━┻━━━┻╯╰━┻━━━╯
  


&nbsp;


<a href="https://twitter.com/BrianJosephLeko"><img src="https://raw.githubusercontent.com/BrianLesko/BrianLesko/f7be693250033b9d28c2224c9c1042bb6859bfe9/.socials/svg-white/x-logo-white.svg" width="30" alt="X Logo"></a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <a href="https://github.com/BrianLesko"><img src="https://raw.githubusercontent.com/BrianLesko/BrianLesko/f7be693250033b9d28c2224c9c1042bb6859bfe9/.socials/svg-white/github-mark-white.svg" width="30" alt="GitHub"></a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <a href="https://www.linkedin.com/in/brianlesko/"><img src="https://raw.githubusercontent.com/BrianLesko/BrianLesko/f7be693250033b9d28c2224c9c1042bb6859bfe9/.socials/svg-white/linkedin-icon-white.svg" width="30" alt="LinkedIn"></a>

follow all of these or i will kick you

</div>


&nbsp;


