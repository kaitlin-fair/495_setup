# Setup Assignment Instructions

(1) Set up a GitHub Account and familiarize yourself with how to use it. Here's a great reference used in ECE281: https://usafa-ece.github.io/ece281-book/appendix/github.html

(2) Ensure you have Python downloaded locally to the computer you will use during this course. I used Anaconda to download Python: https://www.anaconda.com/download

(3) Install a code editor. I am using VS Code: https://code.visualstudio.com/download

(4) Install Git: https://git-scm.com/download/win

(5) Link Git to GitHub. I did so using VS Code by clicking the little waving cat on the left vertical toolbar.
For troubleshooting: https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#_open-a-git-repository

(6) Install Nengo (this is what we will use to program neurons) using the following command: 
`pip install nengo`
For troubleshooting: https://www.nengo.ai/nengo/getting-started.html

(7) Install Black using the following command:
pip install black

(7) Fork this repository.

(8) Open single_neuron.py. Edit the title of the plot (line 57) to also display your last name. For me, the title shows "Decoded Neuron Output - Fair". Run your edited code. Your code should return 1 plot that displays the decoded neuron output with your last name in the title. Save this figure in your repository as a Neuron_Output.png (it will also upload as part of your submission and will show me that everything ran properly). Don't worry about understanding this code yet! We will get there around T10.

(9) Run Black to check your code for minor errors and improper formatting using the following command (I did this in the terminal within VS code):
`black --check .`
If the output does not say "All done! ✨ 🍰 ✨ 1 file would be left unchanged.", you'll need to edit the code to resolve the issue. You can take a look at how Black would reformat your code using `black --diff .` Edit the code accordingly to resolve the issue and run again. Repeat until the output is "All done! ✨ 🍰 ✨ 1 file would be left unchanged.". You could also simply run `black .` to automatically make the changes, but I strongly recommend you understand what changes are made prior to submitting your file. For troubleshooting and more ways to use Black: https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html

(10) Upload your code from GitHub into Gradescope under "Setup Quiz" assignment by T4, 1159.
