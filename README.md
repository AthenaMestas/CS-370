# CS-370

Project Overview

For this project, I trained an intelligent pirate agent to navigate an 8×8 maze and reach the treasure. Rather than programming a specific route, I used deep Q-learning so the agent could learn which movements were most effective through trial and error. 

What Code Was Provided & What Did I Create?

I was given starter code for the maze environment (TreasureMaze.py), experience storage (GameExperience.py), and a partially completed Jupyter Notebook (TreasureHuntGame.ipynb). My main contribution was completing the Q-training algorithm in the notebook. I developed the training loop that selects actions, balances exploration with exploitation, saves experiences, trains the neural network using replay batches, and tracks the agent's progress. In my final training run, the pirate won its most recent 32 games, passed the completion check, and successfully reached the treasure from the top-left starting position. These results demonstrated that it learned to navigate the provided maze, although they do not guarantee the same performance in an unfamiliar environment.

What Do Computer Scientists Do, and Why Does It Matter?

Computer scientists solve problems by designing, developing, and improving systems that process information. This course showed me that computer science is not always about giving a program exact instructions; it can also involve creating systems that learn from experience and adapt their behavior.

How Do I Approach a Problem as a Computer Scientist?

I start by identifying the problem, the expected outcome, and any constraints. From there, I break the work into smaller parts, examine the tools or code already available, and decide how to test my solution. With the pirate agent, I had to understand the maze environment and reward system before training the model. I then checked the results, troubleshot issues, and used the agent's performance to evaluate whether my approach was working. 

What Are My Ethical Responsibilities to the End User and the Organization?

As a computer scientist, I have a responsibility to create systems that are reliable, secure, and transparent about their limitations. For users, that includes protecting information, considering fairness, and testing how a system behaves rather than trusting its output without question. For an organization, it also means writing maintainable code, using resources responsibly, and communicating results accurately.=
