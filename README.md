# Virtual Memory Manager Enhancements – x86-64 / QEMU / Perf

This project extends a teaching OS (xv6) to support modern virtual memory mechanisms. Enhancements include:

- Copy-on-write (COW) and demand paging
- Lazy allocation and page fault handling
- Kernel crash-dump support for post-mortem debugging
- Remote GDB stub integration for single-stepping
- Benchmarks comparing COW and large-page modes using `perf`

> 🔒 The complete source is available only to potential employers.  
Please contact me directly if you'd like access for review.

These implementations are part of a larger effort to explore low-level memory management, concurrency, and fault isolation in operating systems.
