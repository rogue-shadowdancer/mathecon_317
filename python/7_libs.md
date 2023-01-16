# how to use libs(package)
## pip(without anaconda)
```shell
pip install package_name
```
## conda
Activate the conda env first.
```shell
conda install package_name
```
# numpy
"The fundamental package for scientific computing with Python"
[numpy website](https://numpy.org/)
Support a large number of **dimensional arrays** and matrix operations.
It also provides a large number of mathematical functions library for array operations.
## why numpy?
 - fast
 - easy
 - wildly used

[A very good introduction to numpy](https://jalammar.github.io/visual-numpy/)
# basic conda commands
```shell
conda --version
conda config --show
conda update conda
conda create -n env_name python=python_version
# the follow 3 commands are the same
conda env list
conda info -e
conda info --envs

conda activate env_name
conda deactivate
conda remove --name env_name --all # delete env + all pkgs
conda remove --name env_name  package_name # delete specific pkg
# get env info
conda env export --name myenv > myenv.yml
# create env with info
conda env create -f  myenv.yml

conda list
conda install package_name
conda install package_name=version
conda update package_name
conda uninstall package_name

# change python version
conda install python=version

conda update python
```