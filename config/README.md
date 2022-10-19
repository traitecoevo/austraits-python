# Jupyter Lab

These are the steps I followed to configure a Jupyter Lab environment.

## Python virtual environment

In my linux machine I use `venv` to set up a default jupyterlab environment

```sh
python3 -m venv ~/proyectos/jupyterlab
source ~/proyectos/jupyterlab/bin/activate
python --version
pip install --upgrade pip
pip install jupyterlab

pip install pandas
pip install pyyaml

#when we have finished
deactivate
```

If everything is setup correctly, activate the environment, move to the working directory and launch jupyterlab

```sh
source ~/proyectos/jupyterlab/bin/activate
cd ~/proyectos/external/austraits-python
jupyter-lab



#when we have finished
deactivate
```
