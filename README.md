# Host Your Own Offline Mapping Server
## What this is - A step-by-step tutorial on how to host an offline basemap for other GeoSpatial applications to use.
### Specific steps are documented in the following [notebook](https://github.com/incubated-geek-cc/offline-mapping-server/blob/master/Host%20Your%20Own%20Offline%20Mapping%20Server.ipynb)

#### Pre-requisites to run jupyter notebook locally
* **Running:** Python 3.7.9
* **Using:** pip 20.2.4
* **OS:** Windows 10

#### Functionality of each .bat file

Filename | Functionality
------------ | -------------
activate_env.bat | activate virtual environment in Windows
pip_freeze.bat | output all python packages into requirements.txt file and overwrites it
pip_install_requirements.bat | pip install all python packages based on requirements.txt file
run_jupyterlab.bat | run jupyter lab
run_jupyter_notebook.bat | run jupyter notebook on port 8889

* Note: A virtual environment had been intiated for this project via the following command virtualenv `.env`