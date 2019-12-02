# Using Black and Flake8 in a pre-commit hook

- https://ljvmiranda921.github.io/notebook/2018/06/21/precommits-using-black-and-flake8/  
- https://black.readthedocs.io/en/latest/version_control_integration.html  
- https://github.com/pre-commit/pre-commit/issues/701 (couldn't use conda)  
- https://pre-commit.com/  

# Notes in setting up this repo
```bash
cd \DIR\
git init
conda create -n py37 python=3.7
conda activate py37
python -m venv .venv
.venv\Scripts\activate
pip install pre-commit
pre-commit --version
#pre-commit run --all-files
pre-commit install
git add demo_file.py
git commit -m "black it"
```

# Try pre-commit
```bash
cd Downloads/repos/
git clone git@github.com:davidbradway/use-pre-commit.git
cd use-pre-commit/
git checkout -b try
conda create -n py37 python=3.7
conda activate py37
python -m venv .venv
.venv\Scripts\activate
pip install pre-commit
pre-commit --version
pre-commit install
git add demo_file.py
git commit -m "try pre-commit"
```