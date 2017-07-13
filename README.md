# Introduction to Programming with Python

## Getting Started (One-time setup)

 * Download Python 3.6: https://www.python.org/downloads/
 
 * Install pip: https://pip.pypa.io/en/stable/installing/
 
 * install virtualenv:
 ```
    pip install virtualenv
 ```

 * Open Terminal
 
 * Navigate to Documents:
 ```
    cd ~/Documents
 ```

 * Clone this tutorial from github:
  ```
     git clone git@github.com:ryan-td/banana.git
  ```
  
  * make a ~/.virtualenvs directory if it does not already exist:
 ```
    mkdir ~/.virtualenvs
 ```
  
 * Create a virtual environment and a bash shortcut:
 ```
    cd ~/.virtualenvs
    virtualenv -p python3.6 banana
    echo 'alias open-banana="source ~/.virtualenvs/banana/bin/activate; cd ~/Documents/banana; export"' >> ~/.bash_profile
 ```
 
  * open a new Terminal window or tab
  
  * this will go to the right directory and activate the virtualenv:
  ```
     open-banana
  ```
 
  * Install required python packages:
 ```
    pip install -r requirements.txt
 ```
 
 
 ## To get started (everytime)
 
 * open Terminal
 
 * this will go to the right directory and activate the virtualenv:
  ```
     open-banana
  ```
 * start the jupyter notebook server:
 ```
    jupyter notebook
 ```
  
 
 
 
 

