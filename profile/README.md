<div align="center">

# LuaByte (`luabytehq`)

**High-Performance Systems Engineering • Runtime Internals • Low-Latency Architectures**

[![Website](https://img.shields.io/badge/Official_Portal-luabyte.com-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://luabyte.com)
[![Discord](https://img.shields.io/badge/Discord-Join_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Q3V3rvy4j8)
[![RSS Feed](https://img.shields.io/badge/RSS_2.0-feed.xml-f97316?style=for-the-badge&logo=rss&logoColor=white)](https://luabyte.com/feed.xml)

<br/>

```
      ___           ___           ___           ___           ___           ___     
     /\__\         /\ \          /\  \         /\  \         /\  \         /\  \    
    /:/  /        /::\ \        /::\  \       /::\  \       /::\  \        \:\  \   
   /:/  /        /:/\:\ \      /:/\:\  \     /:/\:\  \     /:/\:\  \        \:\  \  
  /:/  /  ___   /::\~\:\ \    /::\~\:\  \   /::\~\:\  \   /::\~\:\  \   _____\:\  \ 
 /:/__/  /\__\ /:/\:\ \:\__\ /:/\:\ \:\__\ /:/\:\ \:\__\ /:/\:\ \:\__\ /::::::::\__\
 \:\  \ /:/  / \/__\:\/:/  / \/__\:\/:/  / \/__\:\/:/  / \/__\:\/:/  / \:\~~\~~\/__/
  \:\  /:/  /       \::/  /       \::/  /       \::/  /       \::/  /   \:\  \      
   \:\/:/  /        /:/  /        /:/  /        /:/  /        /:/  /     \:\  \     
    \::/  /        /:/  /        /:/  /        /:/  /        /:/  /       \:\__\    
     \/__/         \/__/         \/__/         \/__/         \/__/         \/__/    
```

<p align="center">
  <b>LuaByte</b> is an independent systems research group and technical media platform dedicated to low-level performance engineering, memory subsystem optimization, kernel latency elimination, and scalable asynchronous backends.
</p>

</div>

---

### Core Research Pillars

We publish deep, microarchitectural breakdowns and zero-fluff engineering guides across five foundational pillars on [luabyte.com](https://luabyte.com):

| Pillar | Focus Areas & Research Scope | Flagship Guides |
|---|---|---|
| **Programming** | Luau virtual machine internals, bytecode dispatch, generational garbage collection, zero-cost abstractions, asynchronous Rust architectures with Axum & Tokio. | • [Architecting Scalable Rust Services with Axum](https://luabyte.com/blog/programming/scalable-rust-web-services-axum)<br/>• [Luau Runtime & Generational Garbage Collection](https://luabyte.com/blog/programming/luau-runtime-architecture-gc-performance) |
| **System** | Windows NT and Linux kernel internals, DPC latency diagnostics, ISR execution queues, Message Signaled Interrupts (MSI Mode), CPU core parking, and timer resolution. | • [Fix DPC Latency & Audio Stutter in Windows 11](https://luabyte.com/blog/system/fix-dpc-latency-audio-crackling-windows-11)<br/>• [Configure MSI Mode in Windows to Fix Input Lag](https://luabyte.com/blog/system/configure-msi-mode-windows-input-lag) |
| **Network** | Low-latency packet routing, bufferbloat mitigation (CAKE / FQ-CoDel), TCP window scaling, BBR congestion control, socket buffer sizing, and high-frequency edge topologies. | • [TCP Window Scaling & BBR Optimization](https://luabyte.com/blog/network/tcp-window-scaling-bbr-optimization)<br/>• [Eliminate Bufferbloat with CAKE & FQ-CoDel](https://luabyte.com/blog/network/eliminate-bufferbloat-cake-fq-codel) |
| **Hardware** | DRAM sub-timings tuning (DDR5), memory refresh cycle physics (tREFI/tRFC), PCIe Gen 5 NVMe thermal throttling boundaries, PMIC power delivery, and micro-benchmarking. | • [DDR5 Sub-Timings Tuning: Boost Frame Pacing](https://luabyte.com/blog/hardware/ddr5-sub-timings-tuning-guide)<br/>• [PCIe 5.0 NVMe SSD Thermal Throttling Benchmarks](https://luabyte.com/blog/hardware/pcie-5-nvme-thermal-throttling-benchmarks) |
| **Gaming** | Real-time graphics engine profiling, frame-time pacing, 1% low FPS stabilization, G-Sync / FreeSync calibration, and DX12 / Vulkan shader compilation pipeline stutter. | • [Shader Compilation Stutter in DX12 & Vulkan](https://luabyte.com/blog/gaming/shader-compilation-stutter-dx12-vulkan)<br/>• [G-Sync, FreeSync & V-Sync Calibration](https://luabyte.com/blog/gaming/gsync-freesync-vsync-calibration) |

---

### Featured Web Utilities

In addition to deep technical journalism, LuaByte engineers free, in-browser utilities built with modern WebAssembly and compiled Rust:

- **[Luau In-Browser Obfuscator](https://luabyte.com/obfuscator)**: Multi-layer AST transformation, control-flow flattening, string virtualization, and bytecode scrambling tailored specifically for the Luau scripting runtime.

---

### Technology & Engineering Stack

Our platform infrastructure and tooling are developed using compiled, memory-safe, low-latency technologies:

```
[ Frontend & SSR ]     Rust • Leptos 0.8 • WebAssembly (WASM) • TailwindCSS
[ Backend & Engine ]   Axum • Tokio Runtime • Tower Middleware • Hyper HTTP
[ Data Persistence ]   PostgreSQL (Connection-Pooled with SQLx)
[ Edge & Media ]       Cloudflare Workers • Cloudflare R2 • Cloudflare Tunnel
[ Scripting & R&D ]    Luau • C/C++ • Python Benchmarking Scripts
```

---

### Community & Leadership

- **Founder & Lead Security Researcher:** [Arga Astri Bimantara](https://github.com/arugaz) (`@arugaz`)
- **Portal:** [https://luabyte.com](https://luabyte.com)
- **Discord Community:** [discord.gg/Q3V3rvy4j8](https://discord.gg/Q3V3rvy4j8)
- **Security & Vulnerability Reporting:** `support@luabyte.com`

<br/>

<div align="center">
  <sub>Copyright 2026 LuaByte. All rights reserved. Built with Rust and Leptos.</sub>
</div>
