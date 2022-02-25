# SCAR Data EDA

## Tools 
---
* WSL (Ubuntu 20.04)
* Vscode (Remote Wsl, Python Extension)
* Python ()

## What is this repo?
---
  This repo compiles my exploration and use of the data made available by the [SCAR](https://www.scar.org/about-us/members/detailed-information/) regarding topics like:
  * Icebergs 
  
## Setup Documentation
---
1) Create python environment (its files should be good inside the project folder)
    ```
    sudo apt install python3-virtualenv
    virtualenv pyEnv
    ```

2) Activate python environment in the command line
    ``` 
    source pyEnv/bin/activate
    ``` 

3) Change in vscode the interpreter to the python inside pyEnv/bin/python3.8 ```ctrl+shif+p > 'Python Interpreter'```
   1) This way you can run the .py with the extension RUN button with the env activated.
   2) Otherwise, you'll have to run it like `python3 fileName.py` and the env activated.

4) Create a git ignore file, for inspo look at this forked repo [.git ignore examples](https://github.com/ArmandoDLaRosa/gitignore)
    > **OPTIONAL** Create a config.ini file for the env variables.
    ```
    nano .gitignore
    ```
    Paste inside the .gitignore the example + add config.ini file's name
5) Install needed libraries for the project
6) Store the requirements in a file
    ```
    pip freeze > requirements.txt
    ```
7) Make sure that there's
   1) No need to rename variable with good names
   2) No blocks of code that could be a function
   3) Documentation to understand the code
   4) No need to use objects (data and behavior)
   5) No variables that should be in the config.ini
   6) No file that should be in the .gitignore

## Resources
[Source of the data files](https://data.npolar.no/dataset/e4b9a604-1b64-4890-9f21-56b5589807c4)
