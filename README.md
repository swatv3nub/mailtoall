# mailtoall
This is a python program to send emails to multiple users at once.
This program will take all the emails from a csv file and send a custom designed email to them.

# Lets set up your gmail account
- first go to your google account > Security > 2-Step verification and turn it on.
- now in the Security main page you will be able to see App password.
- now click App password > Enter your gmail password.
- Now select the app and select the device and click generate.
- Now copy that 16 digit code and keep it with yourself.

# Some prerequisite
- you need to have python in your machine.
- you need to run the following command. <br>
for windows : `pip install -r requirements.txt`<br>
for macOS : `pip3 install -r requirements.txt`

# How to send emails
- first `cd` into `py_module` folder the run the follwing command.
- for macOS or Linux run `cp sample_config.py config.py`
- for windows run `copy sample_config.py config.py`
- edit the config.py file with your required data.
- edit the index.html with your required mailing data.
- `python mail_to_all.py`

# Tracebacks
if you get an error someting like `535, b'5.7.8 Username and Password not accepted.` or `a bytes-like object is required, not 'str'` just update your creadentials in the `config.py`

# Note
Don't make any changes or add any personal information to `sample_config.py`. If you want to add any information to run the program edit your `config.py` file. 👍

# HAPPY CODING