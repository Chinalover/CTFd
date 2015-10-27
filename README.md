![](https://raw.githubusercontent.com/isislab/CTFd/master/CTFd/static/img/logo.png)
====

CTFd is a CTF in a can. Easily modifiable and has everything you need to run a jeopardy style CTF.

Install: 
 1. `./prepare.sh` to install dependencies using apt.
 2. Modify [CTFd/config.py](https://github.com/isislab/CTFd/blob/master/CTFd/config.py) to your liking.
 3. Use `python serve.py` in a terminal to drop into debug mode.
 4. [Here](https://github.com/isislab/CTFd/wiki/Deployment) are some deployment options

remeber to edit the config.py to change the domain of your webstie
and the smtp username,passsword in utils.py also need to be edit.
the function of edit user message may have bug ,pay attention to it.
don't use the flask,it's so terrible,see (https://github.com/isislab/CTFd/wiki/Deployment.
NJUPT ctf practice website:http://ctf.nuptsast.com
Logo by [Laura Barbera](http://www.laurabb.com/)
