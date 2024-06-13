# AOGS-2024-Workshop
This repository comprises notebooks for the AOGS2024 Workshop related to the CMIP6 dataset.

# Getting Started
The notebooks cover:

- accessing the cmip6 dataset from different data sources.
- plotting key variables from the cmip6 dataset.
- producing climate stripes from the accessed cmip6 dataset.

# Requirements
Clone this repository into your local directory.
```
git clone https://github.com/WCRP-CMIP/AOGS-2024-Workshop.git
cd AOGS-2024-Workshop
```
Install and activate the virtual environment **cmip6env** to run the notebooks using Python 3.
```
python3 -m venv cmip6env
source cmip6env/bin/activate
```
Install the requirements.txt file 
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

# Running Notebooks
```
cd notebooks
jupyter lab <notebook>
```

