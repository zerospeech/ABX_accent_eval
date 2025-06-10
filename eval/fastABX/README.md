# ABX Evaluation with FastABX

This workflow uses [bootphon/fastabx](https://github.com/bootphon/fastabx).

## From `.h5f` Feature Files

1. **Convert Features**  
   Transform `.h5f` feature files using the conversion script:

   ```bash
   convert_features.py
   ```
2. **Run ABX Evaluation**
Execute the ABX evaluation script:
  ```bash
  uv run run_fastabx.py
  ```
