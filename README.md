# Efficient Meta Subspace Optimization

This project includes the code accompanying the submission to AutoML 2022 entitled "Efficient Meta Subspace Optimization".

The code implements a meta optimizer which is applied to the subspace optimization paradigm, and used to optimize the 
loss function of Robust Linear Regression, described in section 4.2 of the paper:

Ke Li, Jitendra Malik, "Learning to Optimize", ICLR 2017.

The code runs three algorithms:

- SESOP: The Sequential Subspace Optimization (SESOP) algorithm described in:  
Narkiss, G. and Zibulevsky, M. (2005). Sequential subspace optimization method for large-scale
unconstrained problems. Technical Report CCIT 559, Technion – Israel Institute of Technology, 
Faculty of Electrical Engineering.
- RB: A Rule based algorithm described in Section 3.3 of the paper
- MSO: The meta optimizer described in Algorithm 1 in the paper.


Requirements
------------
- Python 3.7.2
- PyTorch


Run
---

python automl.py

<!--
Citation
--------
Please cite this work in your publications if it helps your research:


	@article{choukroun2021meta,
	  title={Meta Subspace Optimization},
	  author={Choukroun, Yoni and Katz, Michael},
	  journal={arXiv preprint arXiv:2110.14920},
	  year={2021}
	}
-->

