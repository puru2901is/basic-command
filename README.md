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

### Requirement file in python

```
#You can install all these dependencies at once using:
pip install -r requirements.txt
#If you want to generate a requirements.txt from your current virtual environment, you can use:
pip freeze > requirements.txt

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

