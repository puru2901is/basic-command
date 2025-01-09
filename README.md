# basic-command

### 1. Install Dependencies

#### Using Conda (Recommended)

1. Create a new conda environment:
   ```
   conda create -n <env name>
   ```

2. Activate conda environment:
   ```
   conda activate <env name>
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

### 2. Delete an Environment in Conda

1. Get the list of existing env
```
conda env list
```

2. Deactivate the conda env
```
conda deactivate
```

3. Delete an env
```
conda remove --name <env name> --all
```

