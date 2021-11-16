# undergrad-outreach
This repository will be used in the technical sessions for undergraduate students. It contains instructions on how how to download and install git and python. It also contains a set of instructions on how to set up a virtual environment.

## Session preparation
### Downloads
1. Create an account on [Github](https://github.com/) if you do not have one.
2. Download and install [Git](https://git-scm.com/)
           #### Configure git
           
3. Download and install [Python](https://www.python.org/downloads/)


### Virtual environment.
To be able to run the notebooks we will use during the sessions, do the following:

1. Open your command prompt.
2. Clone this repository and cd into it

    `git clone https://github.com/DeKUT-DSAIL/undergrad-outreach.git`
        
    `cd undergrad-outreach`
      
3. Create a [virtual environment](https://docs.python.org/3/tutorial/venv.html)

    On Linux `python3 -m venv iot-env` or On Windows `python -m venv iot-env`
4. Activate it
On Linux
`source iot-env/bin/activate`
or On Windows
`iot-env\Scripts\activate.bat`
5.  Update pip

        pip install --upgrade pip
6. Install the requirements

        pip install -r requirements.txt
