Welcome at the first School Of AI session.
To beging you have to setup your environment.
For that use conda package manager:
https://conda.io/miniconda.html

After you've installed conda, create an environment with the environment.yml file:
conda env create -f environment.yml

List the available environment:
conda env list

You should see the SchoolOfAI environment:
SchoolOfAI_S1

Activate the environment with:
conda activate SchoolOfAI_S1

In the console you should see the environment is active:
console starts with '(SchoolOfAI_S1)'

Now, you can run the jupyter notebooks with:
jupyter-notebook <filename.ipynb>

To deactivate the environment, use the following command:
conda deactivate
