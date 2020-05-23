# vehicles-images-detector
This is a Backpropagation Neural Network used to recognize images belonging to 3 different classes: *Car*, *Truck* and *Motorcylcle*.

## Running on Google Colab
You could run this Jupyter notebok on Google Colab using this [link](https://colab.research.google.com/github/mnmallea/vehicles-images-detector).

## Running locally
You need to install [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/). And you should make `conda` available on your OS path.

Then you should `cd <repo_path>` on a terminal and run:
```bash
conda env create -f environment.yml # installs project dependencies
conda activate vehicle_recognizer # activates environment
jupyter notebook # opens notebook
```
