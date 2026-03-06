# DCGC

## Installation
Install dependencies:
```bash
pip install -r requirements.txt
```

## Example Results
Typical output for node classification (Cora):
```
Training Cora | Nodes=64 | Run 1/5: 100%|████████████████████████████████████| 200/200 [00:06<00:00, 31.76it/s, Loss=0.0364, Val Acc=0.7800]
{'accuracy': 0.87, 'f1_score': 0.86, ...}
```
Where accuracy, f1_score, precision, recall, roc_auc are reported per run.

## Notes
- For reproducibility, set SEED and experiment parameters as needed.
- All dependencies are listed in requirements.txt with exact versions.

## Installation
Install dependencies:
```bash
pip install -r requirements.txt
```

## Run Example

# DCGC

## Installation
```bash
pip install -r requirements.txt
```


## Usage
Run node classification experiment:
```bash
python train_main.py --dataname 'cora' --epochs 300 --foldername 'logger_folder' --gpu 0
```

## Results
Example output:
```
Training Cora | Nodes=64 | Run 1/5: ... [Loss=0.0364, Val Acc=0.7800]
{'accuracy': 0.87, 'f1_score': 0.86, ...}
```
Accuracy, f1_score, precision, recall, roc_auc are reported per run.

## Notes
- Set SEED and experiment parameters for reproducibility.
- All dependencies are listed in requirements.txt with exact versions.