# Installation
With [conda](https://docs.conda.io/en/latest/miniconda.html):
```
git clone "https://github.com/lucalazzaroni/Autonomous-Agents.git"
cd Autonomous-Agents
conda create -n AAgents python=3.8
conda activate AAgents
pip install -U pip
pip install -r requirements.txt
```

With python virtualenv (make sure you have installed python 3.8 and the virtualenv package):
```
git clone "https://github.com/lucalazzaroni/Autonomous-Agents.git"
cd Autonomous-Agents
python -m venv AAgents
. AAgents/bin/activate
pip install -U pip
pip install -r requirements.txt
```
On UNIX devices the ```. AAgents/bin/activate``` command must be replaced with ```source venv/Scripts/activate```.

# Execution
You can execute the Jupyter notebook by using [vscode](https://code.visualstudio.com/) and the dedicated [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) or using Python Jupyter package.
## vscode
```
cd Autonomous-Agents
code .
```
## Jupyter Notebook
```
pip install jupyterlab
jupyter-lab
```
You should now be able to launch the ```gym_tutorial.ipynb```.

Enjoy!