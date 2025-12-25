# kianv-rv32-linuxcore
Linux-only RV32IMA RISC-V CPU core with Sv32 MMU and SSTC
# KianV RV32 LinuxCore

**Linux-only RV32IMA RISC-V CPU core with Sv32 MMU and SSTC**

KianV RV32 LinuxCore is a **hardwired, Linux-first RISC-V CPU core** designed exclusively to run full Linux systems.

---

## Key Characteristics

- **ISA:** RV32IMA
- **MMU:** Sv32
- **Privilege Modes:** M-mode + S-mode (Linux-capable)
- **Timer Extensions:** SSTC
- **Atomics:** A-extension (Linux required)
- **Target OS:** Full Linux, XV6, RTOS, Baremetal, ...
- **SoC Independence:** Yes (CPU core only)

---

## Reported CPU Information

A Linux system running on this core reports:

```
processor   : 0
hart        : 0
isa         : rv32ima_zicntr_zicsr_zifencei_zaamo_zalrsc_sstc
mmu         : sv32
uarch       : kianv
mvendorid   : 0x0
marchid     : 0x2b
mimpid      : 0x0
```
