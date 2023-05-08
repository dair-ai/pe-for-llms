# Prompt Engineering for LLMs - Notebooks and Exercises

Welcome to the notebooks and exercises for the Prompt Engineering for LLMs course.

## 1. Sign up for Openai and Serp API

To run the notebooks in this repo, you are required to sign up for an OpenAI paid account, as well as a free serpapi account. 

### OpenAI

Sign up a paid account here: https://platform.openai.com/. Once done, you can generate an API key.

### Serp API

Sign up a free account here: https://serpapi.com/. You will need to verify your email address as well as enter a phone number. 
Once done, you can generate an API key 

## 2. Check out the repo

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

## 3. Setup the environment

### Conda

If you don't have conda, you can install it [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/).

Once installed, run the following command to create a new environment called `pe-for-llms`. 

```sh
conda create -n pe-for-llms
```

Next, activate the conda environment.

```sh
conda activate pe-for-llms
```

Finally, add the kernel to Jupyter.

```sh
python -m ipykernel install --user --name pe-for-llms
```

### Python environment

If you don't want to use conda, you can create a virtual environment using Python's `venv` module.

```sh
python3 -m venv .venv
```

Next, activate your environment (the command below is for Linux)
```sh
source .venv/bin/activate
```

## 4. Install the packages

Next, install the dependencies inside the requirements.txt file.

```sh
pip install -r requirements.txt
```

That's it! You're all setup to start working on the notebooks and exercises.