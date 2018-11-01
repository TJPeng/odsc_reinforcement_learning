# Intro to RL
### Environment setup
- change the name of the yml file to environment.yml
- create new conda env using the yml file: `conda env create -f environment.yml python=3.6`
- source activate env_name


### Notes from class
conda env create -n rl_env python=3.6 --file rl_env.yml

```bash
git clone https://github.com/openai/gym.git
cd gym
pip install -e '.[atari]'
```
move the .py files to the gym repo. 
