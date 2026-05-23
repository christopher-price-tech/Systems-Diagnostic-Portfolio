The Problem: Faced performance bottlenecks and intermittent service instability while running resource-intensive AI workloads on high-end integrated hardware.

The Diagnosis: Discovered that default service configurations were failing to leverage hardware-specific compute engines (XMX), resulting in CPU throttling and inefficient memory management.

The Solution: Refined service lifecycle constraints using systemd and cgroups to prioritize P-core execution. Implemented a memory-optimized quantization strategy to align workload demands with unified memory architecture, achieving consistent, high-speed inference performance.
