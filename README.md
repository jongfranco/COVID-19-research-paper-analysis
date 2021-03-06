# COVID-19-research-paper-analysis
Taking massive amounts of research papers and using machine learning &amp; other analytics to help make them consumable.

## Development Information

### How to install:

Prerequisites:
 - Anaconda
 - Git

Run the following commands:

`git clone https://github.com/The-Lycaeum/COVID-19-research-paper-analysis.git`

`cd COVID-19-research-paper-analysis`

`conda env create -f environment.yml -n covid-papers`

This creates the environment with the correct dependencies.  To access the environment:

`conda activate covid-papers`

During development, more packages might be required to run.  You can use `pip install` to add new packages, but a better way would be to add the package name to the environment.yml file, so everyone will be able to use it. 

After you add the packages to the environment.yml, you can use `pip install`, or you can also sync your environment to yml file with:

`conda env update -f environment.yml -n covid-papers`


## Directory Structure

### Data directory

Data is stored in the `src/data` directory.  There are 4 sub-directories in `src/data`: `data/raw`, `data/interim`, `data/processed`, and `data/other`. More about these divisions below.

Since we don't want to store the data on Github, the data directory & its sub-directories should be empty except for specific .git files, and the `download_data.py` script.  Running this script should automatically download the raw data into your `src/data/raw` directory.

### Data sub-directories

#### data/raw

#### data/interim

#### data/processed

#### data/other