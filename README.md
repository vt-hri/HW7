# HW7

Dylan Losey, Virginia Tech.

In this homework assignment we will use behavior cloning to learn the robot's policy.

## Install and Run

```bash

# Download
git clone https://github.com/vt-hri/HW7.git
cd HW7

# Create and source virtual environment
# If you are using Mac or Conda, modify these two lines as shown in [HW0](https://github.com/vt-hri/HW0)
python3 -m venv venv
source venv/bin/activate

# Install dependencies
# If you are using Mac or Conda, modify this line as shown in [HW0](https://github.com/vt-hri/HW0)
pip install numpy pybullet torch
```

## Assignment

Your goal is to modify the robot's motion so that it clearly conveys its goal to human onlookers. 
There are initially two cubes on the table: the robot is programmed to move to cube 1, but the user does not know which cube that is.
Modify your code as needed to complete the following steps:
1. initial go through. explain how to modify the following in the code: the number of hidden layers and the size of each layer, the learning rate, the batch size
2. train on small distribution, test on other distribution
3. train on large distribution, test on small distribution
4. train with less examples