# 🐍 Introduction to Python
*Managed, maintained and run by the Scientific Software Group at the Institute of Cancer Research.*

## 🚀 Overview of the course
This is an introductory course for those seeking to learn Python. The course is split into two parts
- **Part A**: An introduction to programming in Python
- **Part B**: Basic programming with Python

Part A is designed for those with no prior exposure to programming, whilst part B is for those with some exposure to programming, Python or otherwise.

The former has a strong focus on the fundamentals of the language with short exercises peppered throughout to affirm your understanding. 
The latter runs at a sligthly faster pace, and whilst having a simlar course structure and content, involves more complex problems and goes slightly further.

Each course is self contained enough to be taken independently, though you may wish to take them in term to reinforce and build upon your understanding.


## ⚠️ Before you start!

This course is delivered in the form of *Jupyter Notebooks*, and is intended to be worked on in an interactive (live-coding) sort of way. 
Before you join the course, we therefore ask you to have installed *Jupyter Lab* on your own laptop, and to bring your laptop with you to the session.


### 🖥️ Recommended installation procedure

We recommend installing Python and Jupyter Lab as part of the Anaconda Distribution.

1. Head to [this link](https://www.anaconda.com/download#download-section) and download Anaconda for your relevant operating system.
    - If there is an option to select the Python version, select a 3.x. The default download choice should be 3.x.
2. Open up the installer and follow the default installation procedure.
    - If there is an option to "Add Anaconda to my PATH environment variable", ensure this is checked.
    - If these is an option to "Register Anaconda as my default Python", ensure this is checked.


### ☑️ Validating your installation

Once the download has completed, we will need to open a terminal

- **Windows users**
    1. Press start
    2. Type "Anaconda PowerShell" and open the application
- **MacOS users**
    1. Press cmd
    2. Type "Terminal" and open the application

Once you have opened the terminal type the following command and press enter:

```shell
python --version
```

This should print something to your terminal that looks similar to `Python 3.x.y :: Anaconda 2023 ...`

Now type the following command into your terminal and press enter:

```shell
jupyter lab
```

This should stream an output to your terminal, and start a Jupyter Lab session inside your browser. The browser sesion should look a bit like this:

<img src=graphics/jupyter_lab.JPG width="400">

If you run into any permission issues with the download or installation, please contact helpdesk@icr.ac.uk.
If you have any issues verifying your installation, please contact scsoftware@icr.ac.uk.

### 🗃️ Downloading the repository

For those familiar with `git`, simply navigate to a directory you want to keep the files in, then:

```shell
git clone git@github.com:instituteofcancerresearch/intro-to-python.git
cd intro-to-python
jupyter lab
```

Otherwise, download and decompress the zip files manually as shown below

<img src=graphics/zip_download.JPG  width="600">

Assuming you have decompressed the zip file within the default "Downloads" folder, open up your terminal once again, then

- **Windows Users**
    ```shell
    cd Downloads
    cd intro-to-python
    jupyter lab
    ```
- **Mac OS users**
    ```shell
    cd ~/Downloads
    cd intro-to-python
    jupyter lab
    ```

### 🖥️ Not-Recommended alternative

If necessary there is the option to uise an online version of Jupyter Lab, though this is not recommended as it is not as reliable as the local installation and you will not be able to keep and return to your work in the same way. To access this version click:  
[Jupyter online](https://jupyter.org/try-jupyter/lab/?path=notebooks%2FIntro.ipynb)

You will still need to download the files as per the instructions above, and then upload them into this online version of Jupyter Lab. The sub directory structure will need to be created manually.