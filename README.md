<div align="center">

# Deepak Pandey

<p align="center">
  <a href="https://github.com/deepak-pandey2005">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=58A6FF&background=00000000&center=true&vCenter=true&width=650&height=50&lines=Systems+%26+Low-Level+Software+Engineer;Building+bare-metal+NullOS+in+Rust+%26+x86_64+ASM;Writing+Linux+kernel+drivers+%26+zero-copy+engines;Mechanical+sympathy+from+silicon+to+userspace" alt="Typing SVG" />
  </a>
</p>

[![NullOS](https://img.shields.io/badge/Kernel_Dev-NullOS-7952B3?style=for-the-badge&logo=rust&logoColor=white)](https://github.com/deepak-pandey2005/NullOS)
[![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://github.com/deepak-pandey2005)
[![Rust](https://img.shields.io/badge/Rust-DEA584?style=for-the-badge&logo=rust&logoColor=black)](https://github.com/deepak-pandey2005)
[![Linux](https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/deepak-pandey2005)
[![Assembly](https://img.shields.io/badge/x86__64_ASM-000000?style=for-the-badge&logo=gnubash&logoColor=white)](https://github.com/deepak-pandey2005)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://github.com/deepak-pandey2005)

---

</div>

```text
┌──(deepak@baremetal)-[~/kernel]
└─$ cat sysinfo.log
─────────────────────────────────────────────────────────────────────────────
Host Architecture:  x86_64 Bare-Metal / Linux 6.x
Execution Model:    Ring 0 Kernelspace ⟷ Ring 3 Userspace Isolation
Specialization:     Operating Systems, Linux Drivers, Storage Engines, Networking
Primary Toolchain:  C (C99/C11), Rust, x86_64 Assembly (NASM/GAS), Go, Bash
Low-Level Core:     4-Level Paging, APIC/IDT, MMIO, DMA, Slub/Buddy Allocators
Systems Tooling:    QEMU, GDB, Valgrind, Make, CMake, GCC, LLVM, Perf, Wireshark
Active Research:    SMP Scheduling, VirtIO Network Stack, Driver Subsystems
─────────────────────────────────────────────────────────────────────────────
```

## 🔬 About Me

I am a systems developer passionate about peeling back layers of abstraction to understand how hardware, kernels, and compilers interact. My work spans writing bare-metal x86_64 operating systems, implementing Linux device drivers, analyzing network datapaths at line rate, and architecting persistent storage engines.

- ⚙️ **Core Focus**: OS development, memory management (Paging, Slub/Buddy allocators), interrupt dispatching, and low-level concurrency.
- 🛠️ **Current Research**: SMP scheduling, VirtIO network drivers, and Linux kernel subsystem internals.
- 🎯 **Engineering Philosophy**: *Mechanical sympathy, craftsmanship, and deterministic performance from bootloader to userspace.*

---

## 🚀 Featured Systems & Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/deepak-pandey2005/NullOS">🖥️ NullOS — Bare-Metal 64-Bit OS</a></h3>
      <p>Custom, bare-metal 64-bit operating system for <code>x86_64</code> engineered from scratch in Rust, Assembly, and C.</p>
      <ul>
        <li>UEFI firmware handoff & bootloader protocol integration</li>
        <li>Virtual memory manager (4-level paging) & frame allocator</li>
        <li>APIC / PIC interrupt handling, preemption, and Ring 3 userspace isolation</li>
        <li>SMP (Symmetric Multiprocessing) and VirtIO networking foundation</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black" alt="Rust"/>
        <img src="https://img.shields.io/badge/Assembly-333333?style=flat-square&logo=assembly&logoColor=white" alt="ASM"/>
        <img src="https://img.shields.io/badge/QEMU-FF6600?style=flat-square" alt="QEMU"/>
      </p>
      <details>
        <summary><b>🔍 View NullOS Architecture Blueprint</b></summary>
        <br/>
        <pre>
[ UEFI Firmware / Bootloader ]
               │
               ▼
[ Long Mode (64-bit) & GDT/TSS Initialization ]
               │
               ▼
[ 4-Level Paging (PML4) & Physical Frame Allocator ]
               │
               ▼
[ IDT (Interrupt Descriptor Table) & Local APIC ]
               │
               ▼
[ Preemptive Multitasking & Scheduler ]
               │
               ▼
[ Ring 3 Userspace Isolation & Fast Syscalls ]
        </pre>
      </details>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/deepak-pandey2005/CoreMonitor">🛡️ CoreMonitor — Low-Latency IDS & Analyzer</a></h3>
      <p>High-performance network traffic analyzer and intrusion detection system.</p>
      <ul>
        <li>Pure <b>C low-level datapath engine</b> for zero-copy packet sniffing & line-speed protocol parsing</li>
        <li>Stateful intrusion & anomaly detection algorithms</li>
        <li><b>Go upper orchestration layer</b> for telemetry streaming, storage, and live terminal dashboard</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"/>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
        <img src="https://img.shields.io/badge/PCAP-167C80?style=flat-square" alt="PCAP"/>
      </p>
      <details>
        <summary><b>🔍 View CoreMonitor Datapath Pipeline</b></summary>
        <br/>
        <pre>
[ Network Interface Card ]
            │ (AF_PACKET / Raw Sockets)
            ▼
[ C Datapath: Zero-Copy Ring Buffer ]
            │
            ▼
[ Protocol Parser (Eth ➔ IPv4/IPv6 ➔ TCP/UDP) ]
            │
            ▼
[ Stateful Intrusion & Anomaly Engine ]
            │ (IPC / Shared Ring Buffer)
            ▼
[ Go Orchestration Layer ➔ InfluxDB / TUI Dashboard ]
        </pre>
      </details>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/deepak-pandey2005/LINUX_DRIVER">🐧 Linux Kernel Driver Development</a></h3>
      <p>Hands-on implementations of Linux device drivers and kernel subsystems.</p>
      <ul>
        <li>Character device drivers with ioctl, sysfs, and procfs interfaces</li>
        <li>Hardware interrupt handling (top/bottom halves, tasklets, workqueues)</li>
        <li>Memory-mapped I/O, DMA, and race-condition prevention (spinlocks, mutexes)</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"/>
        <img src="https://img.shields.io/badge/Linux_Kernel-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
        <img src="https://img.shields.io/badge/GDB-E05D44?style=flat-square" alt="GDB"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/deepak-pandey2005/RustKV">📦 RustKV — Persistent Key-Value Engine</a></h3>
      <p>High-performance embedded persistent storage engine in Rust.</p>
      <ul>
        <li>Log-Structured Merge-tree (LSM) architecture with Write-Ahead Logging (WAL)</li>
        <li>Immutable MemTable flushing and SSTable format design</li>
        <li>Crash-resilient recovery mechanisms and bloom-filter lookup optimization</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black" alt="Rust"/>
        <img src="https://img.shields.io/badge/Storage-Engine-3DDC84?style=flat-square" alt="Storage"/>
      </p>
    </td>
  </tr>
</table>

<br/>

<div align="center">

### 📌 Live Repository Spotlights

<a href="https://github.com/deepak-pandey2005/NullOS">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=deepak-pandey2005&repo=NullOS&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=79C0FF&text_color=C9D1D9" alt="NullOS Repo" />
</a>
<a href="https://github.com/deepak-pandey2005/CoreMonitor">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=deepak-pandey2005&repo=CoreMonitor&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=79C0FF&text_color=C9D1D9" alt="CoreMonitor Repo" />
</a>

</div>

---

## 🛠️ Technical Arsenal

<div align="left">

| Domain | Technologies & Competencies |
| :--- | :--- |
| **Languages** | `C (C99/C11)`, `Rust`, `x86_64 Assembly (NASM/GAS)`, `Go`, `Bash`, `Python` |
| **Kernel & OS Internals** | 4-Level Paging, Physical Frame Allocator, Virtual Memory, Interrupt Handling (APIC/IDT), Task Scheduling, Context Switching, Ring 0/Ring 3, Syscalls |
| **Linux Subsystems** | Kernel Modules, Character Devices, Platform Drivers, Device Trees, ioctl, sysfs, eBPF, kprobes |
| **Systems Tooling** | `QEMU`, `GDB`, `LLDB`, `Make`, `CMake`, `Valgrind`, `Objdump/Readelf`, `Perf`, `Wireshark`, `Git` |

</div>

---

## 📊 Engineering Activity & Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=deepak-pandey2005&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=79C0FF&text_color=C9D1D9" alt="GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deepak-pandey2005&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top Languages" height="165" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=deepak-pandey2005&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=FF7B72&currStreakLabel=79C0FF" alt="GitHub Streak" />

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
