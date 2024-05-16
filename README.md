# ECE 495 Setup Assignment Instructions

## Required Software and Virtual Environment

(1) Set up a GitHub Account and familiarize yourself with how to use it. Here's a great reference used in ECE281: https://usafa-ece.github.io/ece281-book/appendix/github.html

(2) Fork this repository, [this one](https://github.com/kaitlin-fair/495_tutorials), and [this one](https://github.com/kaitlin-fair/495_labs).

(3)  For this course, you will need a Python environment that uses **python 3.10.11** with specific software packages listed in requirements.txt in this repository. [Download Python 3.10.11](https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe) - This link will download the *.exe file for Python 3.10.11. Double click the downloaded file to start the installer. Be sure to check the box that says add to PATH!

(4) Install VS Code: https://code.visualstudio.com/download

(5) Install Git: https://git-scm.com/download/win

(6) Link Git to GitHub. I did so using VS Code by clicking the little waving cat on the left vertical toolbar.
For troubleshooting: https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#_open-a-git-repository

(7) Create a virtual environment using Python 3.10.11. The process to do so is to create a new environment using Python 3.10.11, activate the new environment, then download the packages using the requirements.txt file. I will provide instructions on how to do this *within VS Code*. Going this route requires that you have this virtual environment in each 495 folder you intend to work in. Copy/pasting doesn't always work, so you may need to repeat this process for each folder you will use.

If you are using Anaconda, these commands should do the trick:  
`conda create --name 495venv python=3.10` -- This command gives your new environment a name of *495venv*, however you can name it whatever you'd like.  
`conda activate 495venv` -- This command activates the environment so that you can install other programs within that environment. You might see the name inside of your brackets change from *base* to the name of your new environment.

If you are using Windows without Anaconda, these commands should work inside of your Command Prompt (**note: must use python 3.10**):  
Use your path to your downloaded Python 3.10.11 in the following command (the path below is only an example of what it might look like):  
`C:\Users\C2XName\AppData\Local\Programs\Python\Python310\python.exe -m venv 495venv` -- This command gives your new environment a name of *495venv*  
Navigate to the `Scripts` folder within your virtual environment and type the command `.\activate` -- This command activates the environment so that you can install other programs within that environment. You might see the name inside of your brackets change from *base* to the name of your new environment. 
  
Note: If you are using Linux or Mac, please let me know and I can find someone to provide assistance if needed.
  
(8) Once you have activated your environment, cd to the directory in which your requirements.txt is stored, then run the following command:  
`pip install -r requirements.txt`  
  
(9) From your activated terminal, launch your code editor. If you're using VS code, this command should do it: `code .` Within VS Code, in the search bar at the top type `>Terminal: Create New Terminal`. Select your _495venv_ environment if/when prompted. 
  
## Test your environment

(1) Open `nengo_495setup.ipynb`. Try to run. It may ask you to install a Jupyter extension - if it does, do it! If it runs properly, move to step 2.

(2) Edit the title of the plot (line 57) to also display your last name. For me, the title shows "Decoded Neuron Output - Fair". Run your edited code. Your code should return 1 plot that displays the decoded neuron output with your last name in the title. Run again and save your file so that the updated plot shows in your notebook. Don't worry about understanding the code yet! We will get there later.

(3) Upload _only_ your `nengo_495setup.ipynb` from GitHub into Gradescope under "Setup Lab" assignment by T4, 1159. You are encouraged to schedule time for EI to debug as needed: [Book here](https://outlook.office.com/bookwithme/user/94f514961fa3476ab9598d4a2173d076@afacademy.af.edu?anonymous&ep=plink)
