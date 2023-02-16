# Bayesian Parameter Estimation Guest Lecture -- Prof. Rachel Kurchin
This repo contains some papers to read as well as the demonstration notebook!

## Setup
If you want to run the notebook yourself, you'll need a Python environment with all the packages that get imported. This is relatively simple to achieve with conda using the included `environment.yml` file:

1. Create the environment by running `conda env create -f environment.yml`
2. Activate it with `conda activate bpe`
3. Now create a jupyter kernel using `python -m ipykernel install --user --name bpe`
4. Now if you open the notebook via `jupyter notebook BPE_guest_lecture.ipynb` and select the `bpe` kernel from the dropdown, all the code should (hopefully) run!