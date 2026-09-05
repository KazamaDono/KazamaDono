<div align="center">

<!-- HEADER -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=%24+sudo+./kazamadono;Security+Researcher+%7C+Systems+Engineer+%7C+Exploit+Dev" alt="Typing SVG" />

<br>

<!-- SOCIAL BADGES -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayukotsu)
[![Website](https://img.shields.io/badge/spectra--vrg.org-0d1117?style=for-the-badge&logo=firefoxbrowser&logoColor=00ff41)](https://spectra-vrg.org)
[![GitHub](https://img.shields.io/badge/GitHub-KazamaDono-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KazamaDono)
[![Followers](https://img.shields.io/github/followers/KazamaDono?style=for-the-badge&logo=github&color=0d1117&labelColor=0d1117&logoColor=00ff41)](https://github.com/KazamaDono?tab=followers)
[![Views](https://komarev.com/ghpvc/?username=KazamaDono&style=for-the-badge&color=0d1117&label=VIEWS)](https://github.com/KazamaDono)

</div>

<!-- ABOUT -->
## `> cat /etc/motd`

```
I break things to understand them, then build tools so machines can break them faster.
```

Offensive security researcher and AI/ML engineer focused on **automated vulnerability discovery**.  
Currently building AI agents that find real bugs autonomously — not theoretical, reproducible.

<!-- RESEARCH -->
## `> cat /var/log/research.log`

Vulnerability research across government, enterprise, and open-source targets. Highlights below — full list is longer.

#### Acknowledged by

<div align="center">

![NASA](https://img.shields.io/badge/NASA-0B3D91?style=for-the-badge&logo=nasa&logoColor=white)
![Google](https://img.shields.io/badge/Google-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Microsoft](https://img.shields.io/badge/Microsoft-5E5E5E?style=for-the-badge&logo=microsoft&logoColor=white)
![DHS](https://img.shields.io/badge/Dept._of_Homeland_Security-003366?style=for-the-badge&logo=homeland&logoColor=white)
![DNFSB](https://img.shields.io/badge/Defense_Nuclear_Facilities-1a1a2e?style=for-the-badge&logoColor=white)
![WHO](https://img.shields.io/badge/World_Health_Org-0093D5?style=for-the-badge&logo=who&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

</div>

<br>

<table>
<tr>
<th>Target</th>
<th>Finding</th>
<th>Class</th>
</tr>

<!-- MMI / MOBILE -->
<tr>
<td><b>Google (Gmail)</b></td>
<td>Authentication bypass in Google's account recovery system by exploiting an Android MMI code vulnerability</td>
<td><img src="https://img.shields.io/badge/MMI-ff0000?style=flat-square" /></td>
</tr>
<tr>
<td><b>Android</b></td>
<td>MMI abuse for OTP bypass — affecting millions of devices</td>
<td><img src="https://img.shields.io/badge/MMI-ff0000?style=flat-square" /></td>
</tr>

<!-- GOV / HIGH-PROFILE -->
<tr>
<td><b>NASA</b></td>
<td>BAC leading to authentication bypass (CSBF Aquila system) — <a href="https://spectra-vrg.org/hackers-handbook/Bypassing_Auth_CSBF.html">writeup</a></td>
<td><img src="https://img.shields.io/badge/Auth_Bypass-ff6633?style=flat-square" /></td>
</tr>
<tr>
<td><b>Defense Nuclear Facilities Safety Board</b></td>
<td>Blind time-based SQL injection</td>
<td><img src="https://img.shields.io/badge/SQLi-cc0000?style=flat-square" /></td>
</tr>
<tr>
<td><b>Dept. of Homeland Security</b></td>
<td>ClickJacking + Reflected client-side DoS via unsanitized search parameter</td>
<td><img src="https://img.shields.io/badge/Web-ff6633?style=flat-square" /></td>
</tr>

<!-- LOW-LEVEL: PARSON -->
<tr>
<td><b>Parson (C library)</b></td>
<td>15+ vulns: stack buffer overflow in <code>person_sprintf</code>, heap over-read in UTF-8 validation, integer overflow in serialization, thread-unsafe globals / UAF, TOCTOU in serialize size/write pass, HashDoS via deterministic djb2, uncontrolled recursion (4 vectors)</td>
<td><img src="https://img.shields.io/badge/Low--Level-8b00ff?style=flat-square" /></td>
</tr>

<!-- LOW-LEVEL: FASTSOCKET -->
<tr>
<td><b>Fastsocket (kernel module)</b></td>
<td>Heap buffer overflow in <code>fsocket_fd_set</code>, stack buffer overflow in argument parsing, use-after-free in pool allocator</td>
<td><img src="https://img.shields.io/badge/Low--Level-8b00ff?style=flat-square" /></td>
</tr>

<!-- AI / JAILBREAKS -->
<tr>
<td><b>Google Gemini</b></td>
<td>Jailbreak (Potato x Charlie)</td>
<td><img src="https://img.shields.io/badge/AI-00bfff?style=flat-square" /></td>
</tr>
<tr>
<td><b>Microsoft Phi-3-Mini</b></td>
<td>Jailbreak (Potato x Charlie)</td>
<td><img src="https://img.shields.io/badge/AI-00bfff?style=flat-square" /></td>
</tr>
<tr>
<td><b>Deepseek</b></td>
<td>Jailbreak</td>
<td><img src="https://img.shields.io/badge/AI-00bfff?style=flat-square" /></td>
</tr>
<tr>
<td><b>Alibaba Qwen3:1.7B</b></td>
<td>14 jailbreak exploits</td>
<td><img src="https://img.shields.io/badge/AI-00bfff?style=flat-square" /></td>
</tr>

<!-- WEB -->
<tr>
<td><b>Iconic</b></td>
<td>Reflected CSTI → XSS chain via AngularJS 1.8.1, input filter bypass via double URL encoding, CORS misconfiguration, CSP bypass + 6 more</td>
<td><img src="https://img.shields.io/badge/Web-ff6633?style=flat-square" /></td>
</tr>
<tr>
<td><b>YouTube</b></td>
<td>Race condition</td>
<td><img src="https://img.shields.io/badge/Web-ff6633?style=flat-square" /></td>
</tr>
</table>

<br>

<div align="center">

*...and more across healthcare, education, and enterprise targets.*

</div>

<!-- TECH STACK -->
## `> ls /opt/toolkit/`

<div align="center">

#### Languages
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=ffd343)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![x86 Assembly](https://img.shields.io/badge/x86_ASM-654FF0?style=for-the-badge&logo=assemblyscript&logoColor=white)

#### Offensive Security
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=hackthebox&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=nmap&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-BF0A30?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Nuclei](https://img.shields.io/badge/Nuclei-6C3AED?style=for-the-badge&logo=target&logoColor=white)
![SQLMap](https://img.shields.io/badge/SQLMap-CC0000?style=for-the-badge&logo=databricks&logoColor=white)
![GDB/PEDA](https://img.shields.io/badge/GDB%2FPEDA-333333?style=for-the-badge&logo=gnu&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

#### Engineering & AI
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<!-- PROJECTS -->
## `> ls -la ./arsenal/`

<table>
<tr>
<td align="center" width="33%">

<a href="https://github.com/KazamaDono/deepvoid">
<img src="https://img.shields.io/badge/DEEPVOID-0d1117?style=for-the-badge&logo=radar&logoColor=00ff41" />
</a>

**Omni-Recon Engine**  
<sub>Automated reconnaissance & vulnerability assessment. Enter a URL, get a full attack surface map.</sub>

`nuclei` `sqlmap` `dalfox` `katana`

</td>
<td align="center" width="33%">

<a href="https://github.com/KazamaDono/7">
<img src="https://img.shields.io/badge/SEVEN-0d1117?style=for-the-badge&logo=openai&logoColor=00ff41" />
</a>

**Voice AI Assistant**  
<sub>Agentic voice AI with tool-calling, security skills, and hologram UI. Fully local via Ollama.</sub>

`langchain` `ollama` `pyqt5` `speech`

</td>
<td align="center" width="33%">

<a href="https://github.com/KazamaDono/Ghosttrigger">
<img src="https://img.shields.io/badge/GHOSTTRIGGER-0d1117?style=for-the-badge&logo=ghost&logoColor=00ff41" />
</a>

**Auth Bypass Scanner**  
<sub>Automated scanner for UI-based authentication bypass in web applications.</sub>

`selenium` `bypass` `auth` `scanner`

</td>
</tr>
</table>

<!-- GITHUB STATS -->
## `> cat /var/log/stats.log`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=KazamaDono&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9&ring_color=00ff41&count_private=true" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=KazamaDono&hide_border=true&background=0d1117&ring=00ff41&fire=ff6633&currStreakLabel=00ff41&sideLabels=c9d1d9&dates=555555&currStreakNum=00ff41&sideNums=00ff41" width="49%" />

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KazamaDono&layout=compact&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&langs_count=8" width="40%" />

</div>

<!-- TROPHIES -->
<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=KazamaDono&theme=matrix&no-frame=true&no-bg=true&column=7&margin-w=10" width="90%" />

</div>

<!-- ACTIVITY GRAPH -->
## `> tail -f /var/log/activity.log`

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=KazamaDono&theme=github-compact&hide_border=true&bg_color=0d1117&color=00ff41&line=00ff41&point=ffffff&area=true&area_color=00ff4130)](https://github.com/KazamaDono)

</div>

<!-- SNAKE -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KazamaDono/KazamaDono/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KazamaDono/KazamaDono/output/github-snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/KazamaDono/KazamaDono/output/github-snake-dark.svg" />
</picture>

</div>

---

<div align="center">

*"The best defense is knowing how the offense works."*

<br>

![AWAKEN AKIRA](https://github.com/user-attachments/assets/ac62deaa-4351-4759-b657-26d5e1e1f3df)

<br>

<sub>*"Mikasa caused the rumbling..." — and I'll die on this hill.*</sub>

<br>

![Made with](https://img.shields.io/badge/Made_with-Coffee_&_Insomnia-0d1117?style=flat-square&logo=buymeacoffee&logoColor=ffdd00)
![OS](https://img.shields.io/badge/OS-Ubuntu_&_Kali-0d1117?style=flat-square&logo=linux&logoColor=00ff41)
![Status](https://img.shields.io/badge/Status-Always_Hacking-0d1117?style=flat-square&logo=statuspage&logoColor=00ff41)

</div>
