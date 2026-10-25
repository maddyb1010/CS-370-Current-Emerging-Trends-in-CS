# CS 370: Pirate Intelligent Agent

## Project Overview

For this project, I worked on a pirate intelligent agent that uses deep Q-learning to find its way through a maze and reach the treasure. I was given a Jupyter Notebook with starter code, along with the TreasureMaze.py and GameExperience.py files that handled the maze environment and stored the agent's experiences. My main responsibility was completing the Q-training algorithm so the pirate could learn how to navigate the maze rather than follow a path that was already programmed for it.

The training process involved letting the pirate try different moves, receive rewards or penalties, and gradually learn which decisions were more successful. I used experience replay and batch training so the model could learn from previous attempts instead of only its most recent actions. I also used a balance of exploration and exploitation, allowing the pirate to try more random moves early in training before relying more on what it had learned. In the completed run, the model reached a 100% recent win rate after 307 epochs and passed the final completion check.

## What Do Computer Scientists Do, and Why Does It Matter?

Computer scientists work on finding ways to solve problems using technology, whether that involves developing software, improving existing systems, or figuring out how to make something work more efficiently. I think an important part of that is understanding the problem itself rather than just focusing on getting the code to run.

This project was a good example of that because the goal was fairly simple: get the pirate to the treasure. The more interesting part was figuring out how to teach the agent to do that on its own. Instead of programming every move, I worked with an algorithm that could learn from its experiences and improve over time. While navigating a maze isn't a particularly complicated real-world problem, the same general approach can be useful in areas like robotics and automation, where systems need to make decisions based on changing conditions.

## How Do I Approach a Problem as a Computer Scientist?

One thing I've learned from working on programming projects is that it helps to understand what each part of the program is supposed to do before making changes. For this project, I needed to understand how the maze worked, what information the pirate received, and how the rewards and penalties affected its decisions. Since some of the code was already provided, I also had to figure out how my training algorithm would work with the existing classes.

I found it useful to have actual training results to look at rather than just knowing that the program ran without errors. The win rate helped show whether the pirate was improving, and the completion check provided another way to test whether it could reach the treasure from different starting positions. This reminded me of some of my other programming projects, where getting something to run correctly was only part of the process. I still needed to make sure it was doing what it was supposed to do.

## What Are My Ethical Responsibilities to the End User and the Organization?

I think one of my biggest responsibilities as a computer scientist is making sure the systems I develop are dependable and don't create unnecessary problems for the people using them. That includes testing for errors, protecting user information, and being aware of situations where an algorithm might produce inaccurate or unfair results. I also have a responsibility to the organization to be honest about problems I find and make sure those issues are addressed rather than overlooked.

Throughout this course, we also looked at how AI systems can develop biases based on their training data. That made me think more about the importance of evaluating how a system makes decisions instead of assuming that its results are always correct. My pirate agent was only learning how to navigate a maze, so the consequences of a mistake were pretty minor. In other applications, though, an incorrect decision could have a much bigger impact on someone.

Since I'm interested in software testing and quality assurance, I think this is especially relevant to what I want to do professionally. A system might appear to work under normal conditions but still have problems that aren't immediately obvious. I think it's important to test different situations, recognize the limitations of a program, and continue looking for ways to improve its reliability.
