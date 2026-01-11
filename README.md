# Albatross

efficient RWKV inference engine

Please check this first: https://github.com/BlinkDL/Albatross/blob/main/benchmark.py

Faster fwd & bwd CUDA kernels: https://github.com/BlinkDL/RWKV-CUDA/tree/main/rwkv7_fast_fused

Faster sampling: https://github.com/Triang-jyed-driung/Rapid-Sampling

Backend: https://github.com/RWKV-Vibe/rwkv_lightning

## Result @ 260109

优化了cuda graph和编译，部分情况下速度提升1.5x，适用于rollout



