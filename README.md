# Bayesian Parameter Estimation Guest Lecture -- Prof. Rachel Kurchin
## Some other references:
- [Bayesim documentation](https://pv-lab.github.io/bayesim/_build/html/index.html)
- [SnS paper](https://www.sciencedirect.com/science/article/pii/S254243511730096X) (featured in slides)
- [Bayesim paper](https://www.sciencedirect.com/science/article/pii/S0010465519300414)
- [Fe in Si paper](https://ieeexplore.ieee.org/abstract/document/9157971) (also featured in slides)

## Setup
If you want to run the notebook yourself, you'll need a Python environment with all the packages that get imported. This is relatively simple to achieve with conda using the included `environment.yml` file:

1. Create the environment by running `conda env create -f environment.yml`
2. Activate it with `conda activate bpe`
3. Now create a jupyter kernel using `python -m ipykernel install --user --name bpe`
4. Now if you open the notebook via `jupyter notebook BPE_guest_lecture.ipynb` and select the `bpe` kernel from the dropdown, all the code should (hopefully) run!