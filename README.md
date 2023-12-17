# FasterDiT
This is a faster implementation of FastDiT (https://github.com/chuanyangjin/fast-DiT), which is an improvement from Diffusion Transformers (DiT) (https://github.com/facebookresearch/DiT).

Please follow FastDiT's instructions for pre-extraction steps as well as the neccessary dependencies for this repo.

The modification includes Flash Attention and Fused Dense adapted from https://github.com/Dao-AILab/flash-attention. 

Please run models_speed.py for the faster implementation version. The model_ablations folder contains scripts for the ablations studies between Flash Attention and Fused Dense.
