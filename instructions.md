Go into the `magicoder` directory and then execute
```bash
pip install -e .
python src/magicoder/generate_data.py  --seed_code_start_index 0 --max_new_data 3 --max_considered_data 5
```
You will need to add your `HF_TOKEN`, `MCLI_API_KEY`, and `url` with the model endpoint.
