# INDBA-ML
Machine Learning Examples with a Python DataScience Stack and Jupyter Notebook


## Install & Start
- Pull the repository
- Switch into the root directory of the repository
- Run `docker-compose up` or (`docker-compose up -d` to avoid information output in the console) in the root directory by using a CLI
    - Ensure that you have installed docker & docker-compose and that the docker daemon is running


## Usage
- All Juypter Notebooks can be found in the folder `jupyter-notebooks`
- To access Jupyter, open your favorite browser and open the webpage `http://localhost:8888`
- All Jupyter Notebooks from the folder `jupyter-notebooks` will be listed on this webpage
	- The `files` (and other folders created by Jupyter) should be ignored

### Prerequisite
- You need to first run all `pip` commands inside the `Prerequisites.ipynb` file. This is needed for the example(s)
	- Open the `Prerequisites.ipynb` and hit the `Run` button. This will install all packages and/or modules
	
	
## Clean-Up Docker Containers
- In order to stop and remove all docker containers, run the following commands:
	- `docker stop twitter-mongodb` (Stops the Mongodb used for storing Data)
	- `docker stop twitter-jupyterNB` (Stops the Jupyter Notebook Server)
	- `docker rm twitter-mongodb` (Removes the Mongodb used for storing Data)
	- `docker rm twitter-jupyterNB` (Removes the Jupyter Notebook Server)