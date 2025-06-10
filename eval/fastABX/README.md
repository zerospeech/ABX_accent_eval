# ABX Evaluation with FastABX

This workflow is based on [bootphon/fastabx](https://github.com/bootphon/fastabx).

### From `.h5f` Feature Files

1. **Convert features**
   Run the conversion script to transform `.h5f` feature files:v
   This script uses

   ```bash
   convert_features.py
   ```
   
3. **Run ABX evaluations**
   Execute:

   ```bash
   uv run run_fastabx.py
   ```

   



