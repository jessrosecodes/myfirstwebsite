# myfirstwebsite


sudo apt install python3.8-venv
python3 -m venv venv

. venv/bin/activate #command to run whenever i am working on this project
#. = shorthand for source
# type // which python3// into terminal, outputshould ave //(venv)//
# which indicates you are running python3 within your virtual envronment
# Terms: Bash, Shell

spacecat@ubuntu:~$ cd source
spacecat@ubuntu:~/source$ cd myfirstwebsite/
spacecat@ubuntu:~/source/myfirstwebsite$ . venv/bin/activate
(venv) spacecat@ubuntu:~/source/myfirstwebsite$ FLASK_APP=server flask run
