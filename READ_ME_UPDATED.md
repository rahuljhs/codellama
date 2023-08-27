## Running the code
```
python3 example_infilling.py --ckpt_dir CodeLlama-7b/ --tokenizer_path CodeLlama-7b/tokenizer.model --max_seq_len 192 --max_batch_size 4

python3 example_instructions.py --ckpt_dir CodeLlama-7b/ --tokenizer_path CodeLlama-7b/tokenizer.model --max_seq_len 512 --max_batch_size 4

python3 .\example_completion.py --ckpt_dir CodeLlama-7b/ --tokenizer_path CodeLlama-7b/tokenizer.model --max_seq_len 128 --max_batch_size 4
```

## Running on windows
```
sudo apt update
sudo apt install dos2unix
dos2unix download.sh
```