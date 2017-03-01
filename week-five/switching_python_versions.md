# Switching Python Versions*	
In class this week (02/27/17) we needed to install [landsat-util](https://pythonhosted.org/landsat-util/) and we did some fancy work in terminal so that those of you who were working with Python 3 could switch down to Python 2. To undo what we did, here's all you have to do:

1. Open terminal
2. Type in the following: `nano ~/.bash_profile`
3. This will open up your bash profile, which can contain different types of configuration information for your console. You should have a line in here that's commented out (lines are commented out if they have a `#` in front of them).
4. Remove the `#` from the line that references `miniconda` 
5. Hit the `control` button + `o` to write and save this to the bash profile
6. Then do `control` + `x` to save this file. 
7. Close your terminal window and restart it. Type `python --version` and you should now be back to running some version of Python 3

If you want to switch back to Python 2, you just need to jump back into your bash profile and re-comment that line. 

*For the record, this is a tiny bit hack-y. If you're going to be working with different versions of Python, I highly recommend using [pyenv](https://github.com/yyuu/pyenv). 

