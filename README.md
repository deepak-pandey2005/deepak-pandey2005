<div align="center">

<a href="https://github.com/deepak-pandey2005">
  <img src="assets/banner.svg" alt="Deepak Pandey — Systems & Low-Level Software Engineer" width="100%" />
</a>

<p align="center">
  <a href="https://github.com/deepak-pandey2005">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=3000&pause=1000&color=58A6FF&background=00000000&center=true&vCenter=true&width=680&height=45&lines=Systems+%26+Low-Level+Software+Engineer;Building+bare-metal+NullOS+in+Rust+%26+x86_64+ASM;Writing+Linux+kernel+drivers+%26+zero-copy+engines;Mechanical+sympathy+from+silicon+to+userspace" alt="Typing SVG" />
  </a>
</p>

[![NullOS](https://img.shields.io/badge/Kernel_Dev-NullOS-7952B3?style=for-the-badge&logo=rust&logoColor=white)](https://github.com/deepak-pandey2005/NullOS)
[![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://github.com/deepak-pandey2005)
[![Rust](https://img.shields.io/badge/Rust-DEA584?style=for-the-badge&logo=rust&logoColor=black)](https://github.com/deepak-pandey2005)
[![Linux](https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/deepak-pandey2005)
[![Assembly](https://img.shields.io/badge/x86__64_ASM-161B22?style=for-the-badge&logo=gnubash&logoColor=white)](https://github.com/deepak-pandey2005)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://github.com/deepak-pandey2005)
![Profile Views](https://komarev.com/ghpvc/?username=deepak-pandey2005&color=58A6FF&style=for-the-badge&label=VIEWS)

---

</div>

```text
┌──(deepak@baremetal)-[~/kernel]
└─$ cat sysinfo.log
─────────────────────────────────────────────────────────────────────────────
Host Architecture:  x86_64 Bare-Metal / Linux 6.x
Execution Model:    Ring 0 Kernelspace ⟷ Ring 3 Userspace Isolation
Specialization:     Operating Systems, Linux Drivers, Storage Engines, NetSec
Primary Toolchain:  C (C99/C11), Rust, x86_64 Assembly (NASM/GAS), Go, Bash
Low-Level Core:     4-Level Paging, APIC/IDT, MMIO, DMA, Slub/Buddy Allocators
Systems Tooling:    QEMU, GDB, Valgrind, Make, CMake, GCC, LLVM, Perf, Wireshark
Active Research:    SMP Scheduling, VirtIO Network Stack, Driver Subsystems
─────────────────────────────────────────────────────────────────────────────
```

## 🔬 About Me

I am a systems engineer focused on peeling back layers of abstraction to understand how hardware, kernels, and compilers interact. My work spans building bare-metal `x86_64` operating systems, implementing Linux kernel device drivers, analyzing network datapaths at line rate, and architecting persistent storage engines.

- ⚙️ **Core Focus**: OS internals, virtual memory management (4-level paging, Slub/Buddy allocators), interrupt dispatching, and lock-free / low-level concurrency.
- 🛠️ **Active Research**: Symmetric Multiprocessing (SMP) scheduling, VirtIO network drivers, and Linux kernel subsystem internals.
- 🎯 **Engineering Philosophy**: *Mechanical sympathy, craftsmanship, and deterministic performance from bootloader to userspace.*

---

## 🖥️ Kernel Terminal

```text
┌──(deepak@baremetal)-[~/kernel]
└─$ ./bootctl --inspect
───────────────────────────────────────────────────────────────────────────────
   _   _       _ _  ___  ____
  | \ | |_   _| | |/ _ \/ ___|      Arch     : x86_64 (Long Mode / Ring 0)
  |  \| | | | | | | | | \___ \      Kernel   : NullOS · Linux 6.x Drivers
  | |\  | |_| | | | |_| |___) |     Memory   : PML4 4-Level Paging + Slub
  |_| \_|\__,_|_|_|\___/|____/      Datapath : Zero-Copy Ring + LSM Storage
───────────────────────────────────────────────────────────────────────────────
  [  0.000000] UEFI: Handing off control to 64-bit kernel_main...
  [  0.001420] MMU:  4-level paging enabled (CR3 = 0x0000000000100000)
  [  0.002890] APIC: Local APIC & IDT initialized · SMP cores online
  [  0.004115] VFS:  Char drivers, ioctl, MMIO & DMA ring buffers ready
  [  0.005602] NET:  AF_PACKET zero-copy datapath engine listening
  [  0.006940] KV:   WAL replayed · MemTable & SSTable bloom filters active
  [  OK  ]     System ready. Awaiting ring-3 syscalls... ▌
───────────────────────────────────────────────────────────────────────────────
```

---

## 🛠️ Technical Arsenal

<div align="left">

| Domain | Technologies &amp; Competencies |
| :--- | :--- |
| **Languages** | `C (C99/C11)`, `Rust`, `x86_64 Assembly (NASM/GAS)`, `Go`, `Bash`, `Python` |
| **Kernel &amp; OS Internals** | 4-Level Paging, Physical Frame Allocator, Virtual Memory, Interrupt Handling (APIC/IDT), Task Scheduling, Context Switching, Ring 0/Ring 3, Fast Syscalls |
| **Linux Subsystems** | Kernel Modules, Character Devices, Platform Drivers, Device Trees, `ioctl`, `sysfs`, `procfs`, MMIO/DMA, eBPF, kprobes |
| **Networking &amp; Storage** | `AF_PACKET`, Raw Sockets, Zero-Copy Ring Buffers, Protocol Parsing, LSM-Trees, WAL, SSTables, Bloom Filters |
| **Systems Tooling** | `QEMU`, `GDB`, `LLDB`, `Make`, `CMake`, `Valgrind`, `Objdump/Readelf`, `Perf`, `Wireshark`, `Git` |

</div>

---

## 📊 Engineering Activity & Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=deepak-pandey2005&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=79C0FF&text_color=C9D1D9" alt="GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deepak-pandey2005&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top Languages" height="165" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=deepak-pandey2005&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=FF7B72&currStreakLabel=79C0FF" alt="GitHub Streak" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=deepak-pandey2005&theme=tokyo-night&bg_color=0D1117&color=58A6FF&line=79C0FF&point=C9D1D9&area=true&hide_border=true" alt="GitHub Activity Graph" width="95%" />

</div>

---

## 📬 Let's Connect

<p align="center">
  <a href="mailto:deepak.os.system@gmail.com">
    <img src="https://img.shields.io/badge/Email-deepak.os.system@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/deepak-pandey2005">
    <img src="https://img.shields.io/badge/GitHub-deepak--pandey2005-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://linkedin.com">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

<div align="center">
  <sub><i>"The best way to understand an abstraction is to build what lies beneath it."</i></sub>
</div>
