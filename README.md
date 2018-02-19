## DSSB-Dressing

#### Resources
- [Meeting Notes](https://docs.google.com/spreadsheets/d/1efbMRaKTUslNaygWW0ClOrDtDmz-vBPUSCbdVV24Pdw/edit#gid=255759195)
http://cs231n.github.io/transfer-learning/

#### Team members (In alphabetical order)
- Aniket
- Ankit
- Brandon
- Ian
- Jordan
- Katherine


#### Google Cloud (subjected to changes)
Make sure you communicate with other team members before turning on and off the instances. Before you set up an account (you need a credit card), you can ask Ian to turn on and off the instances for you. The reason why we should use Google Cloud is that it gives us access to GPU's (in the future, we only have a dummy instance rn, but it should be good enough for most computing tasks). You are welcome to develop on your local machine, but it'd be nice if you could sync it on the instance and make sure it also runs smoothly on Google Cloud.


#### Getting started
To work on this repo, run the following commands
```
# clone a local copy
git clone https://github.com/ianbbqzy/DSSB-Toxic

# navigate into the repo
cd DSSB-Toxic

# download the datasets and put them in a new directory "input"

# create a new development branch
git checkout -b <feature_name_here>

```
Make your changes to the new branch and then
```
# See what files have been changed
git status

# add new/altered files
git add <changed_files_here>

# commit your changes
git commit -m "A message describing your changes."

# push your changes to the remote repo
git push origin head
```
Your changes will now appear on github as a new feature branch. Your teammates can review your changes and merge
it into master.

Remember to run `git pull origin master` frequently to get the latest changes.

#### Jupyter Notebook on your machine

First install anaconda

```
# Create a virtual environment
conda create -n toxic python=3.6

# Activate the virtual environment             
. activate toxic

pip install -r requirements.txt  # Install dependencies

#conda install -c conda-forge tensorflow
conda install tensorflow
conda install keras

source deactivate
```

Remember to source the virtualenv b4 you do anything
