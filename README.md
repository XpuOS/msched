# MSched: Memory Scheduling for GPU Multitasking

Paper and code comming soon!

## Demo

MSched significantly improves system throughput (22x) in multi-tasking scenarios with memory oversubscription.

- Hardware: [NVIDIA RTX 5080](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5080/) (16 GB HBM, PCIe 5.0)
- Workloads: **8** [llama.cpp](https://github.com/ggml-org/llama.cpp) instances running [Llama3-8B](https://huggingface.co/meta-llama/Meta-Llama-3-8B) decoding (int8-quantized, 8.5 GB each)
- Scheduling policy: time-sliced round-robin policy

https://github.com/user-attachments/assets/81914903-6f00-4b6f-8b3f-b5a4f24db669
