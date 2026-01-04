---
date: 2025-09-25
description: "This page lists the system requirements to run PCSX2."
draft: false
sidebar_position: 1
title: "System Requirements"
toc: true
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

This page lists the system requirements to run PCSX2.

<table aria-label="4-by-3 table for operating system, CPU, GPU, and RAM requirements">
 <thead>
  <tr>
   <th scope="col"></th>
   <th scope="col">Minimum</th>
   <th scope="col">Moderate</th>
   <th scope="col">Heavy</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td scope="row">OS</td>
   <td>
    <ul aria-label="Minimum operating system requirements">
     <li>Latest[^Windows_10] Windows 10</li>
     <li>macOS 11 (Big Sur)</li>
     <li>Ubuntu 22.04 or other Linux distro[^distros]</li>
    </ul>
   </td>
   <td>
    <ul aria-label="Moderate operating system requirements">
     <li>Windows 11</li>
     <li>macOS 14–15 (Sonoma–Sequoia)</li>
     <li>Ubuntu 25.04 or other Linux distro[^distros]</li>
    </ul>
   </td>
   <td>
    <ul aria-label="Heavy operating system requirements">
     <li>Windows 11</li>
     <li>macOS 14–15 (Sonoma–Sequoia)</li>
     <li>Ubuntu 25.04 or other Linux distro[^distros]</li>
    </ul>
   </td>
  </tr>
  <tr>
   <td scope="row">CPU</td>
   <td>
    <ul aria-label="Minimum CPU requirements">
     <li>x86-64 with SSE4.1</li>
     <li>[PassMark single-thread rating](https://www.cpubenchmark.net/singleThread.html) ≥ 1500</li>
     <li>Two physical cores[^P-cores] with SMT[^SMT]</li>
    </ul>
   </td>
   <td>
    <ul aria-label="Moderate CPU requirements">
     <li>x86-64 with AVX2</li>
     <li>[PassMark single-thread rating](https://www.cpubenchmark.net/singleThread.html) ≥ 2000</li>
     <li>Four physical cores[^P-cores] with or without SMT[^SMT]</li>
    </ul>
   </td>
   <td>
    <ul aria-label="Heavy CPU requirements">
     <li>x86-64 with AVX2</li>
     <li>[PassMark single-thread rating](https://www.cpubenchmark.net/singleThread.html) ≥ 2600</li>
     <li>Six physical cores[^P-cores] with SMT[^SMT]</li>
     <hr />
     <li>Or *M*-series CPU[^Rosetta]</li>
    </ul>
   </td>
  </tr>
  <tr>
   <td scope="row">GPU</td>
   <td>
    <ul aria-label="Minimum GPU requirements">
     <li>Vulkan 1.1</li>
     <li>Direct3D 11[^FL10]</li>
     <li>OpenGL 3.3[^extensions]</li>
     <li>[PassMark G3D Mark rating](https://www.videocardbenchmark.net/high_end_gpus.html) ≥ 600[^GPU_relevance]</li>
    </ul>
   </td>
   <td>
    <ul aria-label="Moderate GPU requirements">
     <li>Vulkan 1.3</li>
     <li>Direct3D 12[^FL11]</li>
     <li>OpenGL 4.6</li>
     <li>Metal[^Metal]</li>
     <li>[PassMark G3D Mark rating](https://www.videocardbenchmark.net/high_end_gpus.html) ≥ 6000[^GPU_relevance]</li>
     <li>4 GB VRAM</li>
    </ul>
   </td>
   <td>
    <ul aria-label="Heavy GPU requirements">
     <li>Vulkan 1.3</li>
     <li>Direct3D 12[^FL11]</li>
     <li>OpenGL 4.6</li>
     <li>Metal[^Metal]</li>
     <li>[PassMark G3D Mark rating](https://www.videocardbenchmark.net/high_end_gpus.html) ≥ 12000[^GPU_relevance]</li>
     <li>8 GB VRAM</li>
    </ul>
   </td>
  </tr>
  <tr>
   <td scope="row">RAM</td>
   <td><ul aria-label="Minimum RAM requirements"><li>4 GB RAM[^precache]</li></ul></td>
   <td><ul aria-label="Moderate RAM requirements"><li>8 GB RAM[^precache]e]lili>ulul>tdt
   <td><ul aria-label="Heavy RAM requirements"><li>16 GB RAM[^precache]</li></ul></td>
  </tr>
 </tbody>
</table>

:::info[Info – Performance]
Hardware requirements can vary drastically between games.

- CPUs that only meet Moderate requirements will struggle with complex games that pushed the PS2 hardware to its limits.
  - CPU-intensive games: [Wiki](https://wiki.pcsx2.net/Category:CPU_intensive_games), [Forum](https://forums.pcsx2.net/Thread-LIST-The-Most-CPU-Intensive-Games)
- Some release titles and 2D games which underutilized the PS2 hardware may run on CPUs rated as low as 1200.
  - CPU-light games: [Forum](https://forums.pcsx2.net/Thread-LIST-Games-that-don-t-need-a-strong-CPU-to-emulate)
- GPUs which meet Moderate requirements should handle the vast majority of games just fine.[^GPU_relevance]
  - GPU performance is based largely on upscaling level and blending accuracy.
  - GPU-intensive games: [Wiki](https://wiki.pcsx2.net/Category:GPU_intensive_games)
- If you have performance issues, please check the [corresponding troubleshooting guide.](../troubleshooting/performance)

:::

## Example Hardware

<table aria-label="2-by-3 table for example CPUs and GPUs from major manufacturers">
 <thead>
  <tr>
   <th scope="col"></th>
   <th scope="col">Minimum</th>
   <th scope="col">Moderate</th>
   <th scope="col">Heavy</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  4 GB of RAM. We recommend at least 32 GB of memory if using this feature.
