# diffusers-scheduler-problem

Install using the following commands

```shell
conda create -n diffusers_test python=3.10
conda activate diffusers_test
conda install  pytorch==2.1.1 pytorch-cuda=11.8 -c pytorch -c nvidia
pip install diffusers==0.24.0 transformers==4.36.2 accelerate==0.25.0 jupyter
```

The notebook `diffusers_scheduler_problem.ipynb` contains the reproduction of the problem.