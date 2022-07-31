## Cooporative Pong
This is a practice repo for multi-agent reinforcement learning.

We use Petting Zoo, a environment API framework similar to Open AI's Gym, but focused on multi-agent systems.
We also leverage Open AI's baselines for implementations of RL algorithms for convenience.

## Setup
Create a virtual environment and install the python package requirements
```
python -m venv <your_env_name>
source activate <your_env_name>
pip install -r requirements.txt
```

If you want to train a model and save the policy, run
```
python main.py
```


To see the policy play, run 
```
python play.py
```

Note: The policy was only trained for about 10 minutes, so we can do more training if better results are desired.
