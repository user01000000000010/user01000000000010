<div align="center">
  <img src="profile_header.jpg" alt="Profile Banner" width="100%" style="border-radius: 12px;" />
  <br />
</div>

working on low-level gpu acceleration, custom cuda kernels, why? because and memory-bound optimizations for modern transformer architectures.

currently exploring hopper (`sm_90`) primitives — focusing on asynchronous data movement with Tile IR, TMA bulk transfers, and hardware barriers to hide memory latency during attention and decode phases.

### Projects
- **[CUDA](https://github.com/user01000000000010/CUDA)** — High-performance acceleration library implementing FlashAttention-3, DeepSeek-style MLA, FP8 PagedAttention, and fully fused in-SRAM blocks.

