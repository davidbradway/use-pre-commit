
https://ljvmiranda921.github.io/notebook/2018/06/21/precommits-using-black-and-flake8/
https://github.com/pre-commit/pre-commit/issues/701

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
git commit -m "new"
