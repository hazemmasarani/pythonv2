### 1. Create a Virtual Environment

```bash
python3 -m venv ~/.myenv
```

### 2. Activate the Virtual Environment

- For **macOS/Linux**:
  ```bash
  source ~/.myenv/bin/activate
  ```

### 3. Install `ipykernel` Inside the Virtual Environment

```bash
pip install ipykernel
```

### 4. Set the Virtual Environment as the Jupyter Kernel

After installing `ipykernel`, run the following command to register the virtual environment as a Jupyter kernel:

```bash
python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
```

This will make the kernel available in Jupyter, and you should now be able to select the environment in VSCode's Jupyter extension.

### 5. Restart VSCode

Once the virtual environment and kernel are set up, restart VSCode and select the correct kernel from the Python interpreter or Jupyter kernel options.
