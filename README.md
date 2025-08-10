# Inverse Intersections for Boolean Satisfiability Problems

Code implementation of the paper "Inverse Intersections for Boolean Satisfiability Problems" by Homer [arXiv](https://arxiv.org/abs/2501.03281).

The intention of this repository is to test GPT-5's capability in reproducing code from the algorithm in the paper. Almost all the code was generated using GPT-5. There may be subtle bugs. All the code are in the Jupyter notebook [SAT.ipynb](./SAT.ipynb). SAT file instances under the `data` directory is obtained from:

> Holger H. Hoos and Thomas Stützle: SATLIB: An Online Resource for Research on SAT. In: I.P.Gent, H.v.Maaren, T.Walsh, editors, SAT 2000, pp.283-292, IOS Press, 2000. SATLIB is available online at [www.satlib.org](www.satlib.org).

All the instances are from the SATLIB's `Uniform Random-3-SAT/uf20-91`  which are all satisfiable.

Install dependencies using Poetry using `poetry install`.
