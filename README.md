# Prompt Engineering for LLMs - Notebooks and Exercises

Welcome to the notebooks and exercises for the Prompt Engineering for LLMs course.

## 1. Check out the repo

```sh
git clone https://github.com/dair-ai/pe-for-llms.git
cd pe-for-llms
```

If you already have the repo, go into it and make sure you have the latest.

```sh
cd pe-for-llms
git pull origin master
```

If you have downloaded the zipped file instead, unzip it and go into the directory.

```sh
cd pe-for-llms
```

## 2. Setup the environment

### Conda

We recommend using conda to manage your Python environment. If you don't have conda, you can install it [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/).

Once installed, run the following command to create a new environment called `pe-for-llms`. This environment will have all the required dependencies to run the notebooks and exercises.

```sh
conda env create -f environment.yml
```

This may take a few minutes. 

Next, activate the conda environment.

```sh
conda activate pe-for-llms
```

### Python environment

If you don't want to use conda, you can create a virtual environment using Python's `venv` module.

```sh
python3 -m venv pe-for-llms
```

Next, install the dependencies inside the requirements.txt file.

```sh
pip install -r requirements.txt
```

That's it! You're all setup to start working on the notebooks and exercises.