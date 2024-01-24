# course-ds-base

## Preparation

### 1. Fork / Clone this repository

```bash
git clone https://github.com/Alashmony/dvc-course-base.git
cd dvc-course-base
```


### 2. Create and activate virtual environment

Create virtual environment named `dvc-venv` (you may use other name)
```bash
python -m venv dvc-venv
```

Activate the new Virtual Env on Mac
```
echo "export PYTHONPATH=$PWD" >> dvc-venv/bin/activate
source dvc-venv/bin/activate
```
Activate the new Virtual Env on Windows

```
cd '\dvc-venv\Scripts'
.\activate
```
or

```
.\dvc-venv\Scripts\activate
```

Install python libraries

```bash
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```

Add Virtual Environment to Jupyter Notebook

```bash
python -m ipykernel install --user --name=dvc-venv
``` 

Configure ToC for jupyter notebook (optional)

```bash
jupyter contrib nbextension install --user
jupyter nbextension enable toc2/main
```

## 3. Run Jupyter Notebook

```bash
jupyter notebook
```

