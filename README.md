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
     git clone git@github.com:ryan-td/learn_coding.git
  ```
  
  * make a ~/.virtualenvs directory if it does not already exist:
 ```
    mkdir ~/.virtualenvs
 ```
  
 * Create a virtual environment and a bash shortcut:
 ```
    cd ~/.virtualenvs
    virtualenv -p python3.6 learn_python
    echo 'alias learn-py="source ~/.virtualenvs/learn_python/bin/activate; cd ~/Documents/learn_coding; export"' >> ~/.bash_profile
 ```
 
  * open a new Terminal window or tab
  
  * this will go to the right directory and activate the virtualenv:
  ```
     learn-py
  ```
 
  * Install required python packages:
 ```
    pip install -r requirements.txt
 ```
 
 
 ## To get started (everytime)
 
 * open Terminal
 
 * this will go to the right directory and activate the virtualenv:
  ```
     learn-py
  ```
 * start the jupyter notebook server:
 ```
    jupyter notebook
 ```
  
 
 
 
 

