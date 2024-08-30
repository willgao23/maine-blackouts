# maine-blackouts
Navigate to `notebooks/maine-blackout-analysis.ipynb` to view the Jupyter notebook containing all of the Maine blackout data analysis and visualization 

Exported tables and maps can be found in the `notebooks/exports` directory

### Running locally
To install the python codebase, navigate into the folder of this README.md and follow the `pip install` directions below:

Create a new environment (optional):
```
conda create -n maine-blackouts 
conda activate maine-blackouts
```

Pip install requirements:
```
conda install --file requirements.txt
```

Add the `Maine_Power.csv` dataset to the `data` directory

You should now be able to run the Maine blackout analysis Jupyter notebook locally!