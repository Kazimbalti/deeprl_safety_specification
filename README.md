# Safe Deep Reinforcement Learning for Probabilistic Reachability and Safety Specifications

PyTorch implementation of safety specification algorithms in _Safe Deep Reinforcement Learning for Probabilistic Reachability and Safety Specifications_. See the [article](https://arxiv.org/abs/2002.10126) for the detailed description.

### Requirements
* [cplex](https://pypi.org/project/cplex/)
* [gym](https://github.com/openai/gym)
* [JSAnimation](https://pypi.org/project/JSAnimation/)
* [jupyterlab](https://github.com/jupyterlab/jupyterlab)
* [mujoco](http://www.mujoco.org/)
* [mujoco-py](https://github.com/openai/mujoco-py)
* [pytorch](https://pytorch.org/)
* [seaborn](https://seaborn.pydata.org/)
* [tensorboard](https://www.tensorflow.org/tensorboard)
* [tensorboardX](https://github.com/lanpa/tensorboardX)

### Usage
Train the agents using the jupyter notebooks:
```
speculation-reacher.ipynb
speculation-tabular-integrator.ipynb
```
You can also see and print experimental results by running:
```
speculation-reacher-plot.ipynb
speculation-tabular-integrator-plot.ipynb
```

Hyper-parameters we used in the article are the same as what state in speculation-*.ipynb files, but they might be changed in future.
The initial policies and the data associated with them can be found in the following links: [tabular Q-learning (tested on Integrator)](https://drive.google.com/file/d/1_Yejd_B_kvmYxxsD6ffZZHgpsR-KosgE/view?usp=sharing) and [DDPG (tested on Reacher)](https://drive.google.com/file/d/1NFop4eL_6EjdiwmWGyh6hnOp746eEZDj/view?usp=sharing).

### Bibtex
```
@article{Huh,
	Author = {Huh, S. and Yang, I.},
	Date-Added = {2020-02-24 18:17:08 +0900},
	Date-Modified = {2020-02-25 11:28:24 +0900},
	Journal = {arXiv preprint arXiv:2002.10126},
	Title = {Safe Reinforcement Learning for Probabilistic Reachability and Safety Specifications: A {Lyapunov}-based approach},
	Year = {2020}}
```

