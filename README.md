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

### virtual Env
```
# Create virtual environment
python -m venv venv

# Activate it (on Mac/Linux)
source venv/bin/activate
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
### 3. Run Fastapi with uvicorn
```
uvicorn backend:app --reload 
```
### 4. Run Steamlite App
```
streamlit run app.py
```

