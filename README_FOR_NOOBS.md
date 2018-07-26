Make sure you have python 3 installed, if not go to (https://www.python.org/downloads/) and download any python 3+ version

Get Started
  1. Open your terminal. In mac, cmd + space, then type terminal.
  2. Copy the following:
     git clone https://github.com/danysexymexy/Instagram-Bot-Py.git
  3. That command will save the code to your computer. Make sure to save it to a place that you know
  4. Download the chrome driver (https://sites.google.com/a/chromium.org/chromedriver/downloads) and add it on to the /assets folder of the project
  5. Now open terminal once again
  6. Now type 'cd' and then drag and drop the main project folder in terminal. This will read something like this: 'cd /Users/user/Downloads/Instagram-Bot-Py.git'
  7. Now you are inside the project
  
    ** Note: if you are in your work computer, and don't have admin access. Run a python virtual environment.
  ``bash
  python3 -m venv env
  source ./env/bin/activate
  ``
  
  8. Run 'pip3 install selenium'
  9. Run 'pip3 install clarifai'
  10. Run 'pip3 install pyvirtualdisplay'
  11. Run 'pip3 install emoji'
  12. Run 'pip3 install GitPython'
  13. Run 'python3 setup.py install'
  10. Now open quickstart.py in a text-edit
  10. Change/add your Instagram username and password in quickstart.py: insta_username='' and insta_password=''
  11. Save it
  12. Now open terminal and repeat step 6
  13. Run 'python3 quickstart.py'
