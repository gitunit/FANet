- Run `CUDA_VISIBLE_DEVICES=1 python3 speeding.py` for speed comparison
- In our paper, we adopt a single Titan X GPU for evaluation.
- We don't consider the Batch Normalization layer when evaluatin speed, as it can be incorporated into Conv layers.
