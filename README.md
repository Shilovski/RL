# Reinforcement Learning Homework Repository #
## HW1 ##
* part 1 in [`crossentropy_method`](https://github.com/Shilovski/RL/blob/main/crossentropy_method.ipynb) after the __Training loop__ section
* part 2 in [`deep_crossentropy_method`](https://github.com/Shilovski/RL/blob/main/deep_crossentropy_method.ipynb) in the relevant part &mdash; __Homework part II__

Also, the last block of code (after interrupting the LunarLander training cycle with the keyboard) in the second part saves the rendering of the landing of the lunar lander into the `LunarLander.mp4` file in the _content_ folder in Google Colab. 
The training result of agent with an average reward of `55.568` is presented below.

![LunarLander](https://user-images.githubusercontent.com/75098744/225776654-7c0dbc05-8cac-49ef-bda2-ddb4656a4ddb.gif)


## HW2 ##
Presented in the [`seminar_vi`](https://github.com/Shilovski/RL/blob/main/seminar_vi.ipynb) file.

* HW2 Part 1: my MDP converges at 56 iterations
* HW2 Part 2: in __Your PI Results__ compares _PI_ and _VI_ first on FrozenLake __4x4__ then on __8x8__. In both cases, there is a gain in convergence and average reward for __PI__

## HW3 ##
Presented in the [`homework`](https://github.com/Shilovski/RL/blob/main/homework.ipynb) file.

* Part I: Implemented Expected Value _SARSA_ and Expected Value _SARSA_ for __softmax__ policy. Also plotted the results for _EV_SARSA_, _EV_SARSA_SOFTMAX_ and _Q_LEARNING_
* Part II: Training with __experience replay__

## HW4 ##
Presented in the [`homework_pytorch_main`](https://github.com/Shilovski/RL/blob/main/homework_pytorch_main.ipynb) file.
Trained with buffer size `10**6`. The training took approximately 15 hours and 17 minutes, 2010000 iterations with epsilon going up to 0.1; final score: `9.8`.

![output (1)](https://user-images.githubusercontent.com/75098744/230775579-5d7c100c-8600-4aeb-8b69-1bd469640313.gif)
