# Atari Multi-Task Multi-Objective reinforcement learning algorithm

Our code is based off of code from Uber, who we thank. 

The repo has been modified to run both ESMT (multi task) and ESMO (multi objective) algorithms for comparison.

Installation instructions can be found at the original Uber repository at https://github.com/uber-common/deep-neuroevolution.git

## Running the code

Once the environment has been created as per Uber's instructions, one can run the code using the following command:

```
python esmo.py configurations/esmo_riverraid.json
```

Output will be stored in the `logs` directory.

