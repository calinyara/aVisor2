# aVisor2: An ARM based Type-1 Hypervisor for Automotive and Industry Development

aVisor2 is a bare-metal micro-kernelized Type-1 hypervisor which provides basic CPU virtualization and memory virtualization in its kernel and for rest it depends on a managment guest called Service Guest (SG) which provides complete Host hardware access, management interface and guest IO emulation.

- Micro-kernelized architecture
- Multicore Support, three modes available
  - Partition Mode: Guests use fully partitioned pCPUs.
  - Share Mode: Guests may share the same pCPUs.
  - Hybrid Mode: Partition Mode + Share Mode.
- VIRTIO based platform-agnostic IO virtualization
- Web based administration interface with any modern browser
