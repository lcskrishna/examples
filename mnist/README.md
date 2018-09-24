# Basic MNIST Example

```bash
pip install -r requirements.txt
python main.py
# CUDA_VISIBLE_DEVICES=2 python main.py  # to specify GPU id to ex. 2
```

## Running FP-16 Mixed Precision Training for MNIST

```
python main.py --fp16 1 

```
Optionally if you need to apply the loss scaling use --scaling_loss <float> 
