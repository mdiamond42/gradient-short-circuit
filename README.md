# gradient-short-circuit
Gradient Short Circuit: 96% One-Shot Accuracy from Random Init

# Model Checkpoints

Model is hosted on Google Drive due to size constraints.

**Download links:**
-GSC_Gold_OneStep_metadata.txt: https://drive.google.com/file/d/1mxEWuJ-BudnfgfDHvqoKHLBvcGrczb4U/view?usp=drive_link
-GSC_Gold_OneStep.pth  https://drive.google.com/file/d/1_JjiUazniGESGOkaYmXH2t1gDCNmRgUv/view?usp=drive_link
**File details:**
- Format: PyTorch .pt files
- Size: ~XXX MB each
- Contains: Hypertuner weights, optimizer state, training logs

**How to use:**
1. Download checkpoint from link above
2. Place in this `checkpoints/` folder
3. Load in Python:
```python
   import torch
   checkpoint = torch.load('checkpoints/checkpoint_2500k.pt')
```
