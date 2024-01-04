# Setup Assignment Instructions

(1) Set up a GitHub Account.

(2) Ensure you have Python downloaded locally to the computer you will use during this course. I used Anaconda to download Python: https://www.anaconda.com/download

(3) Install a code editor. I am using VS Code: https://code.visualstudio.com/download

(4) Install Git: https://git-scm.com/download/win

(5) Link Git to GitHub. I did so using VS Code by clicking the little waving cat on the left vertical toolbar.
For troubleshooting: https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#_open-a-git-repository

(6) Install Nengo (this is what we will use to program neurons) using the following command: 
pip install nengo
For troubleshooting: https://www.nengo.ai/nengo/getting-started.html

(7) Install Black using the following command:
pip install black

(7) Fork this repository.

(8) Run single_neuron.py. The code should return 1 plot that displays the decoded neuron output. Don't worry about understanding this code yet! We will get there around T10.

(9) Run Black to check your code for minor errors and improper formatting using the following command (I did this in the terminal within VS code):
black --check .
If the output does not say "1 file would be left unchanged", edit the code to resolve the issue and run again. Repeat until the output is "1 file would be left unchanged".

(10) Upload your code from GitHub into Gradescope under "Setup Quiz" assignment by T4, 1159.
