# JPMC Task 3
Starter repo for task 3 of JPMC's Forage program

## Set Up
Just like in the last task, you need to get your local development environment up and running. Given that you completed task 2, you should already have python and node installed and have at least a marginal familiarity with git

First, fork and clone the project repo: https://github.com/theforage/forage-jpmc-swe-task-3
Remember to uncheck the “Copy the main branch only” box in the fork dialog on github. A model answer has been provided in a separate branch from main.
Create a new virtual environment in the project root. Pycharm can do this automatically for you using the “configure python interpreter” option in settings.
Install all project python dependencies. These are listed in the requirements.txt file.
 
Install the necessary dependencies by running `npm install` from the project repo
 
Recall that you must have node 18.10.0 installed for this step to work correctly
 
Start the python server by running server3.py from the project repo like so: python datafeed/server3.py (note it’s important you run it from the root of the project repo) 
 
Start the client by running `npm start` from the project repo
When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets.
Here is an example of what this task looks like in the form of an engineering ticket.

### Purpose
You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor.

Recall that the purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12-month historical average ratio.

### Acceptance Criteria

This ticket is done when the numbers from the python script render properly in the live perspective graph. That means the ratio between the two stock prices is tracked and displayed, the upper and lower bounds are shown on the graph, and an alert is shown whenever the bounds are crossed.
## Refrences:
https://perspective.finos.org/
https://github.com/finos/perspective
