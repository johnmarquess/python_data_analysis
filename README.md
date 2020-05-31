# Python data analysis

This is a repo of basic data analysis technicques using python. The tutorials are stored here as iptython notebooks.

## Tutorial 1 - getting set up

To get started you will need the following:
- python installed on your machine.
- I'm using python version 3.8.2 on a linux [Pop!_OS System 76](https://pop.system76.com/) instal.
- A virtual environment set up.
- A besic set up data python data analysis and visualisation packages.


### Step 1 - install a virtual python environment
- I used [venv](https://docs.python.org/3/library/venv.html) and installed a virtual environment called `.data` in my root folder using the following command `python3 -m venv .data`
- Activate the environment with `source .data/bin/activate`.
- Install the required packages. I usually update pip and install wheel before anything else, as follows: First `pip install -U pip` then `pip install wheel`. This takes care of any errors and warnings.
- The basic packages to get going can be isntalled using `pip install pandas jupyter seaborn`. This will also install any dependencies.
- The list of packages used can be found in the `requirements.txt` file.
- You can also install this using `pip install -r requirements.txt` from your virtual environment.

### Step 2 - test everything is working
- Get started by running the jupyter notebook.
- I like to specify a local IP and port with `jupyter notebook --ip=0.0.0.0 --port=8080`. Because who knows what could be in your `/etc/hosts` file.
- If that worked and the jupyter notebook opened then congratuations. You are up and running.
- If not, leave a comment.

