# mae271b-project

## Virtual Environment Setup
On Ubuntu:
```bash
python3 -m venv 271b-env
source 271b-env/bin/activate
```
On Windows:
```bash
python -m venv 271b-env
.\271b-env\Scripts\activate
```

### Install Requirements
On Ubuntu:
```bash
pip install --no-cache-dir --upgrade pip
pip install -r ./requirements.txt
jupyter labextension install jupyterlab-plotly
jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget
```
On Windows:
```bash
pip install -r .\requirements.txt
```


## Running
On Ubuntu:
Activate your virtual env if you haven't already done so with
```bash
source 271b-env/bin/activate
```
Then launch the jupyter server with
```bash
jupyter lab
```

On Windows:
Activate your virtual env if you haven't already done so with
```bash
.\271b-env\Scripts\activate
```
Then launch the jupyter server with
```bash
jupyter notebook
```