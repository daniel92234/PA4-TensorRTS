# An ENN-based solution for the TensorRTS game.
## Requirements
Use these commands.
Install while conda is deactivated.
```
conda create --name ENN_TensorRTS python=3.8 pytorch -c pytorch
conda activate ENN_TensorRTS
pip install enn_trainer entity_gym torch_scatter
```

## Training
python train.py --config=config.ron --checkpoint-dir=checkpoints
