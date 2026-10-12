# Learn-SecByte-CTF-Labs-Collection-Kernel-Drivers-BYOVD-PowerShell-Evasion-Labs
A curated collection of hands-on cybersecurity CTF labs covering BYOVD Kernel Drivers, LSASS Memory Dumping, Defender Evasion, PowerShell/VBA Macros, MSI Packers, and Scripted Threats from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on Windows kernel driver security, credential protection, evasion techniques, and script-based malware analysis labs designed for cybersecurity students, CTF players, malware analysts, SOC engineers, and threat hunters.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Modern threat actors frequently leverage ring 0 kernel drivers, living-off-the-land scripts, and obfuscated installer packages to bypass endpoint security controls. Hosted on [Learn SecByte](https://learn.secbyte.org/), this collection of CTF challenge labs focuses on practical Windows security mechanics and advanced evasive threats.

From investigating Bring Your Own Vulnerable Driver (BYOVD) attacks and ring 0 kernel driver hooking to analyzing LSASS memory credential access, Windows Defender AV evasion, and deobfuscating PowerShell, VBA macros, HTA, VBScript, Batch, and MSI installers, these exercises build essential technical skills for analyzing sophisticated Windows threats.

---

## Lab Collection & Index

Below is the complete, searchable index of all kernel driver, script malware, and evasion challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Kernel Driver Malware: Hunting a Malicious Driver** | Kernel & Driver Analysis | Ring 0 driver reverse engineering, I/O Control (IOCTL) codes, kernel hooking | [Access Lab](https://learn.secbyte.org/ctf/kernel-driver-malware-hunting-a-malicious-driver) |
| 2 | **Windows Driver Malware: Signed Threats and BYOVD** | Kernel & Driver Analysis | BYOVD exploitation, vulnerable signed driver abuse, kernel memory manipulation | [Access Lab](https://learn.secbyte.org/ctf/windows-driver-malware-signed-threats-and-byovd) |
| 3 | **MSI Malware Analysis: Windows Installer Triage and Unpacking** | Installer & Packaging | Custom MSI tables, embedded WiX scripts, DLL action extraction, installer unpacking | [Access Lab](https://learn.secbyte.org/ctf/msi-malware-analysis-windows-installer-triage-and-unpacking) |
| 4 | **JavaScript Malware Analysis Lab** | Script Deobfuscation | JS deobfuscation, WScript execution, string encoding, DOM-less execution analysis | [Access Lab](https://learn.secbyte.org/ctf/javascript-malware-analysis-lab) |
| 5 | **Batch Malware Analysis: Executing the Scripted Threat** | Script Deobfuscation | Cmd.exe obfuscation, environment variable expansion, downloader loops | [Access Lab](https://learn.secbyte.org/ctf/batch-malware-analysis-executing-the-scripted-threat) |
| 6 | **VBScript Malware Analysis: Scripted Deception** | Script Deobfuscation | VBS deobfuscation, WMI query execution, ActiveX object creation, drop routines | [Access Lab](https://learn.secbyte.org/ctf/vbscript-malware-analysis-scripted-deception) |
| 7 | **HTA Malware Analysis** | Script Deobfuscation | HTML Application execution, mshta.exe abuse, embedded VBScript/JScript triage | [Access Lab](https://learn.secbyte.org/ctf/hta-malware-analysis) |
| 8 | **VBA Malware Analysis: Macros, Obfuscation & Payload Hunting** | Office & Document Security | OLE stream extraction, AutoOpen macros, string deobfuscation, shellcode delivery | [Access Lab](https://learn.secbyte.org/ctf/vba-malware-analysis-macros-obfuscation-payload-hunting) |
| 9 | **Office Macro Malware Analysis** | Office & Document Security | Malicious document triage, VBA code analysis, DDE execution, dropper macros | [Access Lab](https://learn.secbyte.org/ctf/office-macro-malware-analysis) |
| 10 | **PowerShell Malware Analysis** | Script Deobfuscation | PowerShell AST parsing, Base64/gzip decoding, AMSI bypass analysis | [Access Lab](https://learn.secbyte.org/ctf/powershell-malware-analysis) |
| 11 | **Windows Defender Evasion Lab** | Evasion & Obfuscation | AMSI patching, ETW patching, obfuscation techniques, AV bypass mechanics | [Access Lab](https://learn.secbyte.org/ctf/windows-defender-evasion-lab) |
| 12 | **LSASS Memory Analysis: Live Response Investigation** | Credential Access & Forensics | LSASS memory dump triage, Mimikatz artifact extraction, credential hunting | [Access Lab](https://learn.secbyte.org/ctf/lsass-memory-analysis-live-response-investigation) |

---

## Categories

### 1. Kernel Drivers, BYOVD & Low-Level Threats
Deconstruct Ring 0 kernel driver mechanics, analyze I/O Control (IOCTL) codes, and investigate Bring Your Own Vulnerable Driver (BYOVD) attack techniques.
- [Kernel Driver Malware: Hunting a Malicious Driver](https://learn.secbyte.org/ctf/kernel-driver-malware-hunting-a-malicious-driver)
- [Windows Driver Malware: Signed Threats and BYOVD](https://learn.secbyte.org/ctf/windows-driver-malware-signed-threats-and-byovd)

### 2. Defense Evasion & Credential Forensics
Investigate anti-virus evasion, AMSI and ETW bypasses, and execute live-response memory triage on credential processes like LSASS.
- [Windows Defender Evasion Lab](https://learn.secbyte.org/ctf/windows-defender-evasion-lab)
- [LSASS Memory Analysis: Live Response Investigation](https://learn.secbyte.org/ctf/lsass-memory-analysis-live-response-investigation)

### 3. Script Malware & Living-Off-The-Land Vectors
Deobfuscate native Windows scripting payloads written in PowerShell, JavaScript, VBScript, Batch, and HTA.
- [PowerShell Malware Analysis](https://learn.secbyte.org/ctf/powershell-malware-analysis)
- [HTA Malware Analysis](https://learn.secbyte.org/ctf/hta-malware-analysis)
- [VBScript Malware Analysis: Scripted Deception](https://learn.secbyte.org/ctf/vbscript-malware-analysis-scripted-deception)
- [JavaScript Malware Analysis Lab](https://learn.secbyte.org/ctf/javascript-malware-analysis-lab)
- [Batch Malware Analysis: Executing the Scripted Threat](https://learn.secbyte.org/ctf/batch-malware-analysis-executing-the-scripted-threat)

### 4. Office Macros & Installer Unpacking
Extract hidden payloads from Microsoft Office documents, OLE streams, and Windows Installer (MSI) packages.
- [VBA Malware Analysis: Macros, Obfuscation & Payload Hunting](https://learn.secbyte.org/ctf/vba-malware-analysis-macros-obfuscation-payload-hunting)
- [Office Macro Malware Analysis](https://learn.secbyte.org/ctf/office-macro-malware-analysis)
- [MSI Malware Analysis: Windows Installer Triage and Unpacking](https://learn.secbyte.org/ctf/msi-malware-analysis-windows-installer-triage-and-unpacking)

---

## Learning Path

Follow this structured progression path to build technical expertise across Windows kernel security and script analysis:

1. **Phase 1: Script & Document Deobfuscation** — Master basic script triage and macro analysis:
   - [Batch Malware Analysis: Executing the Scripted Threat](https://learn.secbyte.org/ctf/batch-malware-analysis-executing-the-scripted-threat)
   - [JavaScript Malware Analysis Lab](https://learn.secbyte.org/ctf/javascript-malware-analysis-lab)
   - [VBScript Malware Analysis: Scripted Deception](https://learn.secbyte.org/ctf/vbscript-malware-analysis-scripted-deception)
   - [HTA Malware Analysis](https://learn.secbyte.org/ctf/hta-malware-analysis)
   - [Office Macro Malware Analysis](https://learn.secbyte.org/ctf/office-macro-malware-analysis)
   - [VBA Malware Analysis: Macros, Obfuscation & Payload Hunting](https://learn.secbyte.org/ctf/vba-malware-analysis-macros-obfuscation-payload-hunting)

2. **Phase 2: PowerShell & Packaging Analysis** — Decompile installers and analyze complex PowerShell vectors:
   - [PowerShell Malware Analysis](https://learn.secbyte.org/ctf/powershell-malware-analysis)
   - [MSI Malware Analysis: Windows Installer Triage and Unpacking](https://learn.secbyte.org/ctf/msi-malware-analysis-windows-installer-triage-and-unpacking)

3. **Phase 3: Evasion & Memory Forensics** — Triage anti-virus bypasses and credential access attempts:
   - [Windows Defender Evasion Lab](https://learn.secbyte.org/ctf/windows-defender-evasion-lab)
   - [LSASS Memory Analysis: Live Response Investigation](https://learn.secbyte.org/ctf/lsass-memory-analysis-live-response-investigation)

4. **Phase 4: Ring 0 Kernel & Driver Analysis** — Reverse-engineer kernel drivers and BYOVD exploits:
   - [Kernel Driver Malware: Hunting a Malicious Driver](https://learn.secbyte.org/ctf/kernel-driver-malware-hunting-a-malicious-driver)
   - [Windows Driver Malware: Signed Threats and BYOVD](https://learn.secbyte.org/ctf/windows-driver-malware-signed-threats-and-byovd)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and download the exercise files provided on [Learn SecByte](https://learn.secbyte.org/).
3. Utilize static and dynamic analysis tools (e.g., OLETools, CyberChef, x64dbg, IDA Free, Ghidra, WinDbg, Process Hacker, Volatility) inside an isolated sandbox VM.
4. Extract obfuscated payloads, inspect kernel structures, trace credential harvesting activities, and retrieve challenge flags.

---

## Disclaimer

This repository and its linked resources are strictly designed for educational, threat research, and authorized security training purposes. Never execute or analyze kernel drivers, evasion tools, or malware samples on live corporate or production networks.
