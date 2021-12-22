#This project is for setting up NRG Project #






# Virtual Environment Setup
-   Create virtual environment

        mkvirtualenv -p `which python3.6` nrg
 

-   Install dependencies: Create pip.conf from pip.conf.template with placeholders replaced
    
        export PIP_CONFIG_FILE=pip.conf
        pip install -r requirements.txt --extra-index-url https://pypi.python.org/simple


   
  



