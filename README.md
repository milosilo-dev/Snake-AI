# Snake AI
 
Based on the Tutorial: https://www.youtube.com/watch?v=PJl4iabBEz0
Thanks to Patrick Loeber!

# What it dose:

This is built using pytorch and has a nural network that can be trained to play snake!
I found it maxes out at around 50/60 because it will always get into a loop that it can not escape from, I belive that this is because i have not given it any way to detect if it is going in a loop so it just dose. I have also used matplotlib to make a graph the represents its training over time. It can also save the modle os if you have a crash you can restore the modle to its last backup (it backs up every high score).

# install

this project is aimed at linux /debien based systems so if you run install.sh it will install all the dependensys, I would advise useing a vertual enviroment. while it is desined for ubuntu it should be able to run on windows and mac as well as other distros, for this you will have to find the installs your self for all of the dependencys. 

# Run

To run you simply run the agent.py file.