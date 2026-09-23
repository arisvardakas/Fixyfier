<p align="center">
  <a href="https://fixyfier.com">
    <img src="assets/img/logo.png" alt="Fixyfier" width="180" />
  </a>
</p>

<h1 align="center">Fixyfier</h1>

<p align="center">
  <b>Technician-grade Windows repair &amp; maintenance — no bloat, no placebo tweaks, no noise.</b><br/>
  Every task is a documented Windows command, and you see it before it runs.
</p>

<div align="center">

  ![Version](https://img.shields.io/badge/Version-9.1.6-375A7F?style=flat-square)
  ![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-blue?style=flat-square&logo=windows)
  ![Type](https://img.shields.io/badge/Type-System%20Utility-purple?style=flat-square)
  ![Languages](https://img.shields.io/badge/Languages-39-1A8754?style=flat-square)
  [![License](https://img.shields.io/badge/License-Fixyfier%20License%20Agreement-F39C12?style=flat-square)](LICENSE)
  ![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)

</div>

<p align="center">
  <a href="https://apps.microsoft.com/detail/9pp0m68r9b04"><b>Microsoft Store</b></a> &nbsp;&middot;&nbsp;
  <a href="https://fixyfier.com"><b>Website</b></a> &nbsp;&middot;&nbsp;
  <a href="https://fixyfier.com/documentation/"><b>Documentation</b></a> &nbsp;&middot;&nbsp;
  <a href="https://fixyfier.com/troubleshooting/"><b>Guides</b></a> &nbsp;&middot;&nbsp;
  <a href="https://fixyfier.com/#support"><b>Support</b></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/img/fixyfier-dark-mode-interface.png">
    <img src="assets/img/fixyfier-dark-mode-interface.png" alt="The Fixyfier dashboard" width="820">
  </picture>
</p>

---

## Why Fixyfier

Most "optimization" tools are bloated, noisy, or full of tweaks that do nothing.
Fixyfier collects the repair tools Windows already ships with — DISM, SFC, CHKDSK, the
built-in troubleshooters, the network stack commands, the service and package managers
and dozens of buried settings — and puts them one click away.

It is a convenience layer, not a magic fix. **Nothing happens that you could not do
yourself from an elevated terminal**, and you are shown the command line first.

<table>
<tr>
<td width="25%" align="center"><b>No ads</b></td>
<td width="25%" align="center"><b>No account</b></td>
<td width="25%" align="center"><b>No telemetry</b></td>
<td width="25%" align="center"><b>No analytics</b></td>
</tr>
</table>

Settings live in `HKCU\SOFTWARE\Fixyfier`. Nothing runs in the background once the app
is closed, and the only thing Fixyfier ever downloads is the community cleaning-rules
list, on request, straight into memory.

---

## What it does

Over **140 tasks** across **twelve screens**, grouped by what you are trying to achieve.

<table>
<tr>
<td width="33%" valign="top">

### 🖥️ Dashboard
What the machine is, live processor, memory and drive gauges, and a health card: activation, Defender, firewall, system protection, Secure Boot.

</td>
<td width="33%" valign="top">

### 🔧 Fix &amp; Repair
One Fix pass with seven steps, DISM, SFC, CHKDSK, the icon and search caches, Windows Update reset, and every built-in troubleshooter.

</td>
<td width="33%" valign="top">

### 🧹 Cleanup &amp; Optimize
Temp files, the Recycle Bin, thumbnail and app caches, `Windows.old`, restore points, and community cleaning rules — with a dry run first.

</td>
</tr>
<tr>
<td valign="top">

### 📁 Files &amp; Folders
Lock, hide, force-delete, take ownership, repair permissions, and clear hidden attributes across a whole drive.

</td>
<td valign="top">

### 📦 Installed Apps
Store apps and desktop programs in one list with sizes, multi-select uninstall, Reset and Repair, plus a switch for each of **31** preinstalled apps.

</td>
<td valign="top">

### 🌐 Network &amp; Connectivity
Ping, traceroute, IP configuration, Wi-Fi details, open connections, DNS flush, and TCP/IP, Winsock and full stack resets.

</td>
</tr>
<tr>
<td valign="top">

### 🔒 Security &amp; Privacy
Firewall and Smart App Control, plus **54** advertising, suggestion and diagnostic-data settings — each its own switch, or all off in one pass.

</td>
<td valign="top">

### 🛠️ System Tools
Hardware and drive-health reports, startup programs, power plans and battery, Hyper-V and DirectPlay, and app updates through winget.

</td>
<td valign="top">

### 🪟 Windows Tools
Twenty Windows utilities one click away — Event Viewer, Device Manager, Disk Management, Registry Editor, Task Scheduler and the rest.

</td>
</tr>
<tr>
<td valign="top">

### ⚙️ Services
Every Windows service with Windows' own description, what will stop along with it, and no way to disable what Windows needs in order to start.

</td>
<td valign="top">

### 📜 Scripts
Generate a cleanup batch file, build your own, or run your `.bat`, `.cmd`, `.ps1` and `.vbs` files with the rights Fixyfier already has.

</td>
<td valign="top">

### 📚 Troubleshooting Guides
All **72** fixyfier.com guides browsable in the app, and a search box that understands symptoms — type *no sound* and it finds the audio repair.

</td>
</tr>
</table>

---

## How it behaves

> These are the rules the app is built on, not marketing lines.

- **Every command is shown before it runs.** Advanced tasks print the exact command line.
- **There is always a way back.** An advanced task asks Windows for a restore point first.
- **Unknown is a real answer.** Anything Fixyfier could not read says so, rather than showing green or zero.
- **Deletions preview first.** Cleanup tasks offer a dry run that lists what would go, without removing anything.
- **A long run can be stopped.** Output is live, and Stop ends the run rather than the current step.
- **Your files are yours.** Fixyfier never reads, changes or vouches for the scripts in your MyTools folder.

---

## Themes

Light and dark, switchable from the top bar, and the whole app follows.

<table>
  <tr>
    <td align="center">
      <img src="assets/img/fixyfier-light-mode-interface.png" alt="Light theme" width="420"><br>
      <sub><b>Light Theme</b></sub>
    </td>
    <td align="center">
      <img src="assets/img/fixyfier-dark-mode-interface.png" alt="Dark theme" width="420"><br>
      <sub><b>Dark Theme</b></sub>
    </td>
  </tr>
</table>

---

## Languages

Fixyfier ships in **39 languages**, switchable from the top bar and applied immediately.

<details>
<summary><b>See the full list</b></summary>

<br/>

Albanian &middot; Arabic &middot; Bengali &middot; Bulgarian &middot; Chinese (Simplified) &middot;
Chinese (Traditional) &middot; Croatian &middot; Czech &middot; Danish &middot; Dutch &middot;
English &middot; Filipino &middot; Finnish &middot; French &middot; German &middot; Greek &middot;
Hebrew &middot; Hindi &middot; Hungarian &middot; Indonesian &middot; Italian &middot; Japanese &middot;
Korean &middot; Norwegian &middot; Persian &middot; Polish &middot; Portuguese (Brazil) &middot;
Portuguese (Portugal) &middot; Romanian &middot; Russian &middot; Serbian &middot; Spanish &middot;
Spanish (Latin America) &middot; Swahili &middot; Swedish &middot; Thai &middot; Turkish &middot;
Ukrainian &middot; Vietnamese

</details>

---

## Install

Get the signed, always-current build from the Microsoft Store.

<p>
  <a href="https://apps.microsoft.com/detail/9pp0m68r9b04?referrer=appbadge&amp;mode=direct&amp;cid=github_official" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20light.svg" width="200" alt="Get it from Microsoft Store">
  </a>
</p>

**WinGet**

```powershell
winget install --id 9pp0m68r9b04 --source msstore
```

Fixyfier runs as administrator, because most of what it does requires it.

---

## MyTools

Drop a `.bat`, `.cmd`, `.ps1` or `.vbs` file into `Documents\Fixyfier\MyTools` and it appears
as a card straight away — no restart, no right-click, no execution-policy detour. Fixyfier is
already elevated, so your script runs elevated.

The first **three runs are free**. After that it is a one-time unlock in the Microsoft Store:
no subscription, no tiers, and every other feature of Fixyfier works exactly the same either way.

---

<p align="center">
  <b>Fixyfier is free and maintained independently.</b><br/>
  If it saves you time, you can support it here:<br/><br/>
  ❤️ <a href="https://www.paypal.com/donate/?hosted_button_id=5ZA38NSJHMWHJ"><b>Support Fixyfier</b></a>
</p>

<p align="center">
  <sub><a href="https://fixyfier.com/documentation/">Documentation</a> &middot;
  <a href="https://fixyfier.com/troubleshooting/">Troubleshooting Guides</a> &middot;
  <a href="https://fixyfier.com">fixyfier.com</a></sub>
</p>
