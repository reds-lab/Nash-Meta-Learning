# Nash-Meta-Learning
Official implementation of "Fairness-Aware Meta-Learning via Nash Bargaining." We explore hypergradient conflicts in one-stage meta-learning and their impact on fairness. Our two-stage approach uses Nash bargaining to mitigate conflicts, enhancing fairness and model performance simultaneously.


 # Installation  
Step 1: Create a new conda environment:
```
conda create -n nbs_meta python=3.9
conda activate nbs_meta
```
Step 2: Install relevant packages
```
conda install pytorch==1.10.1 torchvision==0.11.2 torchaudio==0.10.1 cudatoolkit=11.3 -c pytorch -c conda-forge
conda install numpy pandas matplotlib tqdm 
conda install conda-forge::scikit-learn
pip install cvxpy
pip install higher
pip install "lale[full]"
```

 # Run "fairness_demo.ipynb"
 The code will run each method for 5 diffrent random seeds and the results will be print at the end.