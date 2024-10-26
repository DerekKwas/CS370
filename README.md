# Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

This project consisted of taking the role of an AI developer for a gaming company.  The company wanted a treasure hunt game where a user tried to reach the treasure before the pirate did which is an AI.  I was tasked with creating an AI that would travel the environment (maze) which consisted of an 8x8 matrix with the cells either containing a 1 or 0 which either
meant the cell was occupied or not, respectively.  The pirate started at the top right cell and must travel to the treasure in the quickest way possible which was in the bottom right cell.  The code given was the TreasureEnvironment.py file that contained the code that set up the environment as well as keeping track of the pirate’s movement and giving rewards
based on the action taken as well as keeping track of the games state.  In the GameExperience.py file, I was also given the experience replay code that stores all the episodes and the states between the initial and final state.  The build model was also given that implements the neural network that will be used for the agent.  Lastly, I was also given the code for the 
Play Game function that sets up the game and determines if the pirate can win the game.  The code that I had to create myself was the Q-training algorithm that was used by the agent to be able to learn the best possible path to the treasure.


# Connect your learning from throughout this course to the larger field of computer science:
## What do computer scientists do and why does it matter?

I believe a computer scientists main job is to gain knowledge of an ongoing problem, whether it be a need for software to perform a certain task, or an upgrade that provides better features and sustainability in systems, develop a plan on how to address said issue and split the solution into multiple bite-sized chunks, and create/develop software that solves/fulfills said problem.


## How do I approach a problem as a computer scientist?

As a computer scientist, I have found that when presented with a problem the best method for me is to split the problem into multiple pieces allowing me to focus on smaller portions of the problem.  With this, design, development, and testing are much easier for me to control and go over, ensuring that everything is working and gives me a sort of step process
where at each step I can keep adding to previous iterations making sure that if I add something to the current version and the program stops working, I can go back and check what change caused the issue.


## What are my ethical responsibilities to the end user and the organization?

My ethical responsibilities to the end user and the organization are to ensure the quality and security of what I am developing.  This is accomplished by following software development standards before, during, and after development making sure that topics such as security are a high priority in development to ensure that confidential data is not easily accessible.
Keeping good documentation on the software can make sure that the end user and the organization are in the know about what is involved with the application and understand how it works.  
