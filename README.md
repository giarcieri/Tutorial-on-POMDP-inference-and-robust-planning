# Tutorial-on-POMDP-inference-and-robust-planning

This is a tutorial for the paper "Bridging POMDPs and Bayesian decision making for robust maintenance planning under model uncertainty: An application to railway systems" (https://arxiv.org/abs/2212.07933), which shows how to infer POMDP model parameter distributions from available data and how to incorporate all distributions into the POMDP solution to derive an optimal policy robust to model uncertainty.

## Installation steps to run the tutorial

Clone repository:
```bash
git clone https://github.com/giarcieri/Tutorial-on-POMDP-inference-and-robust-planning.git
cd Tutorial-on-POMDP-inference-and-robust-planning
```
Create the conda environment:
```bash
conda create -n robust-pomdp python=3.8
conda activate robust-pomdp
```
Install requirements:
```bash
pip install -r requirements.txt
```
Open and run the jupyter notebook.
