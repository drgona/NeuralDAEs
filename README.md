# Neural Differential Algebraic Equations


This is the repository for the paper titled **[Learning Neural Differential Algebraic Equations via Operator Splitting](https://arxiv.org/abs/2403.12938)** by James Koch, Madelyn Shapiro, Himanshu Sharma, Draguna Vrabie, and Jan Drgona.

Neural Differential Algebraic Equations (Neural DAEs) are an extension of the canonical neural timestepper for systems with algebraic constraints. 
Inspired by fractional-step methods, this work leverages sequential sub-tasks to provide updates for algebraic states and differential states.

<p align="center">
  <img src="./figs/fig_01.png" width="500">  
</p>


**Simple tutorial example in Neuromancer**
+ <a target="_blank" href="https://colab.research.google.com/github/pnnl/NeuralDAEs/blob/master/training/tank_dae_example.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> Tank-Manifold example using basic Neuromancer abstractions


**Training and visualization scripts needed for reproducing all paper results**
+ [Neuromancer 1.4 with custom modules for DAE integration](https://github.com/pnnl/NeuralDAEs/tree/master/neuromancer-dae)
+ [Tank-Manifold Property Inference Example](https://github.com/pnnl/NeuralDAEs/blob/master/training/train_manifold.py)
+ [Tank Network Modeling Example](https://github.com/pnnl/NeuralDAEs/blob/master/training/train_network.py)

## Cite as
```yaml
@inproceedings{koch2025,
      title={Learning Neural Differential Algebraic Equations via Operator Splitting}, 
      author={James Koch and Madelyn Shapiro and Himanshu Sharma and Draguna Vrabie and Jan Drgona},
      year={2025},
      eprint={2403.12938},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2403.12938}, 
      volume={},
      number={},
      booktitle={Conference on Decision and Control (CDC)}, 
}
```


## Acknowledgments

This research was supported by the U.S. Department of Energy through the Building Technologies Office under the Advancing Market-Ready Building Energy Management by Cost-Effective Differentiable Predictive Control projects. PNNL is a multi-program national laboratory operated for the U.S. Department of Energy (DOE) by Battelle Memorial Institute under Contract No. DE-AC05-76RL0-1830.

<p align="center">
  <img src="figs/PNNL_logo.jpg" width="500">  
</p>


This research was also supported by the Ralph O’Connor Sustainable Energy Institute at Johns Hopkins University.

<p align="center">
  <img src="figs/JHU_logo.png" width="500">  
</p>



# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
