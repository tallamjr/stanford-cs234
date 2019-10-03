# Assignments


## Assignment 1

This assignment will provide you with practice with fundamental ideas in
sequential decision making and the start of reinforcement learning. We will use
Open AI gym for the programming component.

### Solution

See the solution here

### Tasks

There are 2 parts to this assignment: written and code components. Both parts
are required.

The coding assignment, including some starter code, is available here.

The written homework questions are available here. You can find the tex file
here

### Setup
_Note: Please be sure you have Python 3.6.x installed on your system. The
following instructions should work on Mac or Linux. If you have any trouble
getting set up, please come to office hours and the TAs will be happy to help._

[Optional] virtual environment: Once you have unzipped the starter code, you
might want to create a virtual environment for the project. If you choose not to
use a virtual environment, it is up to you to make sure that all dependencies
for the code are installed on your machine. To set up a virtual environment, run
the following:


```bash
cd assignment1
sudo pip install virtualenv      # This may already be installed
virtualenv .env                  # Create a virtual environment
source .env/bin/activate         # Activate the virtual environment
pip install -r requirements.txt  # Install dependencies
# Work on the assignment for a while ...
deactivate                       # Exit the virtual environment
```

Install requirements (without a virtual environment): To install the required
packages locally without setting up a virtual environment, run the following:

```bash
cd assignment1
pip install -r requirements.txt  # Install dependencies
```

## Assignment 2

In this assignment, you will use Q-learning with function approximators (deep
Q-network) to play games! We will use Open AI gym for the Atari environment.
Please note that it takes more than 12 hours for Pong to train so please start
early.

- Understand the basic Q-learning method.
- Understand the use of experience replay , target network and the selection of
- Hyperparameter tuning.
- Implement and apply a linear approximator on the Pong game.
- Implement and apply the DQN on the Pong game.
- Understand the differences and tradeoffs between these two approximators.

### Tasks

There are 2 parts to this assignment: written and code components.

The coding assignment, including some starter code, is available here.

The written homework questions are available here.

### Setup
Working remotely on Azure
(highly recommended for training on Pong)

As part of this course, you can use Azure for your assignments. We recommend
this route for anyone who is having trouble with installation set-up, or if you
would like to use better CPU/GPU resources than you may have locally. Please see
the set-up tutorial here for more details.
Working locally

While you are waiting for the Azure subscriptions to be set up, you can get
started on all problems except q4 and q5 (Pong).
Note: Please be sure you have Python 3.6.x installed on your system. The
following instructions should work on Mac or Linux. If you have any trouble
getting set up, please come to office hours and the TAs will be happy to help.

[Optional] virtual environment: Once you have unzipped the starter code, you
might want to create a virtual environment for the project. If you choose not to
use a virtual environment, it is up to you to make sure that all dependencies
for the code are installed on your machine. To set up a virtual environment, run
the following:

```bash
cd assignment2
sudo pip install virtualenv      # This may already be installed
virtualenv .env --python=python3.6 # Create a virtual environment
source .env/bin/activate         # Activate the virtual environment
pip install -r requirements.txt  # For Mac, edit this file to change
"tensorflow-gpu" to "tensorflow"
sudo apt-get install cmake       # For Linux
sudo apt-get install zlib1g-dev  # For Linux
sudo apt-get install ffmpeg      # For Linux
brew install zlib                # For Mac
brew install ffmpeg              # For Mac
# Work on the assignment for a while ...
deactivate                       # Exit the virtual environment
```
Install requirements (without a virtual environment): To install the required
packages locally without setting up a virtual environment, run the following:

```bash
cd assignment2
pip install -r requirements.txt  # For Mac, edit this file to change
"tensorflow-gpu" to "tensorflow"
sudo apt-get install cmake       # For Linux
sudo apt-get install zlib1g-dev  # For Linux
sudo apt-get install ffmpeg      # For Linux
brew install zlib                # For Mac
brew install ffmpeg              # For Mac
```


_Notes
NOTE 1: Please install and make sure you're using the tensorflow 1.7 version and
up-to-date numpy.
NOTE 2: Please use Python 3.6.X to develop your code._

### Reference papers
- Human-level control through deep reinforcement learning, V. Mnih et al., Nature, 2015.
- Playing Atari with Deep Reinforcement Learning, V. Mnih et al., NIPS Workshop, 2013.


## Assignment 3

This assignment will provide you with practice with policy gradient and
Multiarmed Bandit. We will use MuJoCo Envinronment, please see the installation
guide.
### Tasks

There are 2 parts to this assignment: written and code components. Both parts
are required.

The coding assignment, including some starter code, is available here.

The written homework questions are available here. Find the source tex file here

### Setup
Note: Please be sure you have Python 3.6.x installed on your system. The
following instructions should work on Mac or Linux. If you have any trouble
getting set up, please come to office hours and the TAs will be happy to help.

[Optional] virtual environment: Once you have unzipped the starter code, you
might want to create a virtual environment for the project. If you choose not to
use a virtual environment, it is up to you to make sure that all dependencies
for the code are installed on your machine. To set up a virtual environment, run
the following:

```bash
cd assignment3
sudo pip install virtualenv      # This may already be installed
virtualenv .env                  # Create a virtual environment
source .env/bin/activate         # Activate the virtual environment
pip install -r requirements.txt  # Install dependencies
# install MuJoCo

pip install mujoco-py==0.5.7
# Work on the assignment for a while ...
deactivate                       # Exit the virtual environment
```
Install requirements (without a virtual environment): To install the required
packages locally without setting up a virtual environment, run the following:

```bash
cd assignment3
pip install -r requirements.txt  # Install dependencies
# install MuJuCo
pip install mujoco-py==0.5.7

```

_Notes
NOTE 1: Please install and make sure you're using the tensorflow 1.7 version and
up-to- date numpy._
NOTE 2: Please use Python 3.6.X to develop your code.
