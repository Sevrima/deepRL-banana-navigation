
# PROJECT-1 Banana-navigation

## 1- Pseducode For the Implemented Algorithm
* Deep Q network with experience replay acheives a good result (after tuning, 500 episodes were needed to solve the problem), thus other algorithms were excluded. 
<p align="center">
    <img src="/images/dqn.png" width=700>
</P>

## 2- Model Network and Tuned Hyperparameters 
* A deep network with four fully connected layers
    - Number of nodes in first hidden layer:    256
    - Number of nodes in second hidden layer:   256
    - Number of nodes in third hidden layer:    64
* gamma = 100
* BATCH_SIZE = 64
* GAMMA = 0.90  
* TAU = 1e-3
* LR = 5e-4
* UPDATE_EVERY = 4
* n_episodes=2000 
* max_t=1000 
* eps_start=1.0 
* eps_end=0.03 
* eps_decay=0.995

## 3- Results
* Score plot, and number of episodes elapsed:
<p align="center">
    <img src="/images/score.png" width=500>
</P>

* Video of trained agent for 500 time steps:
<p align="center">
    <img src="/images/test_video.gif" width=500>
</P>
