# MLwithTenserflow
Udacity Machine Learning with Tensorflow
<h1>Step 1- Install Anaconda</h1>
Install Anaconda - https://www.anaconda.com/products/individual
Installation Instructions - https://docs.anaconda.com/anaconda/install/windows/ <br>
After Installation on Windows a bunch of applications are installed along with Anaconda:<br>
(1) Anaconda Navigator, a GUI for managing your environments and packages<br>
(2) Anaconda Prompt, a terminal where you can use the command line interface to manage your environments and packages<br>
(3) Spyder, an IDE geared toward scientific development<br>
Open Anaconda terminal and type command <br>
<br>
conda list<br>
<br>
- you can chech your own install by this.<br>
To avoid errors later, it's best to update all the packages in the default environment. Open the Anaconda Prompt application. In the prompt, run the following commands:<br>
<br>
conda upgrade conda<br>
conda upgrade --all<br>
<br>
Troubleshooting<br>
If you are seeing the following "conda command not found" and are using ZShell, you have to do the following:<br>

Add export PATH="/Users/username/anaconda/bin:$PATH" to your .zsh_config file.<br>
------<br>
Now, for installing any package you simply have to type conda install package_name in your terminal. For example, to install numpy,type<br>
<br>
conda install numpy<br>
<br>
You can install multiple packages at the same time. Something like<br>
<br>
conda install numpy scipy pandas<br>
<br>
will install all those packages simultaneously. It's also possible to specify which version of a package you want by adding the version number such as<br>
<br>
conda install numpy=1.10<br>
<br>
You can install multiple packages at the same time. Something like conda install numpy scipy pandas will install all those packages simultaneously. It's also possible to specify which version of a package you want by adding the version number such as conda install numpy=1.10<br>
<br>
<h1>Step 2- Running a python script on you cmd</h1>
This is the original window that you will see when you open cmd<br>


<br>
Now is the time when you can create another folder for coursework and set the directory before executing the command to run python script.<br>
For instance, I have created the folder named Udacity/Python and changed the directory as shown<br>

<br>
Furthur, give the command<br>
<br>
python first_script.py <br>
<br>

<br>
if you get the same output as mine, you have done it correct.<br>
<h1>Step 3 - Installing Atom Environment</h1>
Link (For windows) - https://atom.io/ <br>
<h1>Step 4- Installing and Launching Jupyter Notebook</h1>
We will install Jupyter Notebook by giving this command in Anaconda Prompt.<br>
<br>
conda install jupyter notebook<br>
or<br>
pip install jupyter notebook<br>
<br>
and then Jupyter notebook can be launched by this command in cmd or Anaconda prompt (remember to check the directory, as we have installed it through Anaconda, it will be installed in Anaconda directory folder. While launching through cmd, use that directory) 
<br>
jupyter notebook<br>
<br>

<br>
(P.S- I have shifter my Anaconda folder to coursework directory)<br>
You should consider installing Notebook Conda to help manage your environments. Run the following terminal command:<br>
<br>
conda install nb_conda<br>
<br>
Then if you run the notebook server from a conda environment, you'll also have access to the "Conda" tab shown below. Here you can manage your environments from within Jupyter. You can create new environments, install packages, update packages, export environments and more. You can shutdown the entire server by pressing control + C twice in the terminal. Again, this will immediately shutdown all the running notebooks, so make sure your work is saved!<br>
<br>
When you create a new notebook, you should see something like this:<br>
<br>

<br>
For How to get started with Jupyter Notebook : 

