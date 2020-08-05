# Super-Mario-RL

This is a private project to make Super Mairo Agent. :mushroom:


It consists of training an agent to clear Super Mario Bros with deep reinforcement learning methods.

Here is my super mario agent with dueling network. ( trained 7,000 epoach )
![mairo](/mario1.gif)

# Get started

## Install Requirements
* Install [openAI gym](http://gym.openai.com/)
```
pip install 'gym[all]'
```
* Install [Pytorch](https://pytorch.org/)
```
pip install torch torchvision
```
* Install [nes-py](https://pypi.org/project/nes-py/)
```
pip install nes-py
```
* Install [gym-super-mario-bros](https://pypi.org/project/gym-super-mario-bros/)
```
pip install gym-super-mario-bros
```

## Cloning git

```
git clone https://github.com/jiseongHAN/Super-Mario-RL.git
cd Super-Mario-RL
```

# Running

## Train

* Train with dueling dqn.
```
python duel_dqn.py
```

### Return
* score.p : save total score every 50 episode
* *.pth : save weight of q, q_target every 50 training


## Test
* Test and render my agent.
* To test our agent, we need 'q_target.pth' that generated at the training step.
```
python test.py
```
