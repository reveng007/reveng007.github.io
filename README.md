
<!-- ## Welcome to GitHub Pages -->

<!-- <img style="padding-right: 50px;" align="left" src="reveng_rtkit/bat.jpg"> -->

<div style="text-align: center;">
    <img style="padding-right: 50px;" src="reveng_rtkit/bat.jpg" alt="Bat Image">
</div>

## About Me: 
- Hi, this is Soumyanil (aka reveng007).
- Red mind. Blue mission. | Turning attack tradecraft into detections across Cloud & AD | Purple Teaming · Threat Hunting | Black Hat Speaker | CRTO | CRTP
- Former Black Hat Asia, USA, SecTor & Europe 2024, Wild West Hacking Fest 2024 Arsenal Presenter and Former Speaker BSides Singapore 2023.

## What I do:

1. Perform Red/purple Team assessments on Client environments.
2. Perform Threat detections/hunting on Cloud and On-prem environments to help detection engineers in authoring detections for identified bypasses, reducing blind spots across MITRE ATT&CK techniques.
3. Developing and deploying custom detections based on analysis of incidents and relevant adversary TTPs via "Detection as Code".
4. Different EDRs, MDI and other Security Product evaluation.
5. Created Offensive CI/CD Pipelines and automated hunting for sensitive keywords in O365 environments.
6. Perform Network PT and Thick Client Testing assessments.
7. Covert Custom C2 creation and Exfiltration related BOF development for BRC4 and Cobalt Strike.

## Projects I have worked on High Level:

1. **Purple Team Engagements** — \
Adversary Simulation to Detection Validation
Ran 400+ AD attack test cases (ADCS abuse, Kerberoasting, ACL abuse, and more) against MDI's ML-based detections — achieving an 89% alert hit rate and converting previously undetected techniques into validated alerts. Closed 10+ critical detection gaps and expanded SOC detection portfolio by 30% by bridging offensive findings directly into detection logic.

2. **AWS Attack Simulation & Detection Lab + Research (Ongoing)** - \
End-to-end purple team lab mapping Stratus Red Team TTPs to MITRE ATT&CK, with production-ready Sigma and SQL-based detections built on CloudTrail, sysmon and windows eventviewer — covering Initial Access, Execution, and beyond. Actively publishing a blog series documenting each detection's telemetry, pseudocode, query development, noise tuning, and simulation replay. During research, independently discovered a previously documented AWS API that can be abused to tamper with CloudTrail logging (blog coming soon). It is documented but not at all talked about before. \
link - https://soumyani1.medium.com/

3. **Security Product Assessment — EDR, MDI, MDE & PAM** - \
Evaluated detection coverage and abuse potential across enterprise security products. Assessed Microsoft Defender for Identity under real AD attack scenarios, analyzed MDE exclusion visibility and abuse under the "HideExclusionsFromLocalAdmins" policy, performed holistic endpoint security review across MDE, Zscaler, DLP, and BeyondTrust on Windows 11, and discovered multiple UAC bypass paths within BeyondTrust PAM under restricted low-flex environments — each with accompanying detection recommendations.

4. **Offensive Automation — Cloud & CI/CD** - \
Built adversary simulation tooling integrated into organization's automation platform for repeatable cloud attack scenarios and continuous detection testing. Separately, engineered a GitHub Actions CI/CD pipeline enabling remote download, compilation, encryption, and obfuscation of .NET payloads — delivering evasive payloads continuously during purple team engagements.

5. **SharePoint Sensitive Data Hunting** - \
Hunted for exposed sensitive data across live enterprise SharePoint environments using Microsoft Graph API and KQL — identifying blind spots in DLP coverage and generating actionable remediation findings.

6. **Malware & Ransomware Tooling** - \
Developed stealthy ransomware and evasive malware strains for internal red team assessments.


## Courses/ Certifications:
- [Linkedin Learning - Threat Detection](https://drive.google.com/file/d/1qtASkG-7to0DMratbJI_fI1BuscDtL8Y/view)
- [O'Reilly - Wireshark for SecOps](https://www.credly.com/badges/b611cf36-7e31-489b-8944-02087d642968/public_url)
- [Pluralsight - Threat Hunting: Network Hunting](https://app.pluralsight.com/achievements/share/4e93100e-a4d6-4789-a5e7-d6ac1698c56a)
- [KC7Fundation - KQL : Advanced Persistent Analyst](https://kc7cyber.com/certificate/earned/36989)
- [TryHackMe - Attacking and Defending AWS](https://tryhackme.com/certificate/THM-FAQAASBXX0)
- [HackTheBox - Detecting Windows Attacks with Splunk](https://academy.hackthebox.com/course/preview/detecting-windows-attacks-with-splunk)
- [Maldev Academy - Malware Development Modules](https://drive.google.com/file/d/197oCOJqQojcgcJnX2MOb5WQWNTyyJYNc/view)
- [DeepLearning.ai - Red Teaming LLM Applications](https://learn.deeplearning.ai/accomplishments/4ecfdaa0-31b8-4180-859b-b639d49bf05c?usp=sharing)
- [ZeroPoint Security - Certified Red Team Operator/ CRTO](https://eu.badgr.com/public/assertions/pM_ivRXJQ0iuVwdpFVRCdg?identity__email=soumyanilbiswas2018@gmail.com)
- [Pentester Academy - Certified Red Team Professional/ CRTP](https://www.credential.net/cb63b0b6-f75d-4139-adce-03ad8a70af3f)
- [AttackIQ Foundations of Operationalizing MITRE ATT&CK v13](https://www.credly.com/badges/35a3a463-7117-42ed-9dc2-bc26a7cc83ec)
- [Sektor7 RED TEAM Operator: Windows Evasion Course](https://drive.google.com/file/d/1LyrCWgZEmEVpPpLQiQFMZ9zt1_pm210f/view)
- [Antisyphon Training SOC Core Skills](https://drive.google.com/file/d/1Y7subNgM_mdaLcwJYwK8xV6MyzmLqUYZ/view)

---

### _`$ cat /var/www/html/index.html`_

View my <a href="https://reveng007.github.io/blog/" target="_blank">My list of posts</a> !

- <a href="https://reveng007.github.io/blog/2022/03/08/reveng_rkit_detailed.html" target="_blank">How did I approach making linux LKM rootkit, “reveng_rtkit” ?</a>
- <a href="https://reveng007.github.io/blog/2024/01/29/CloudGat-AWS-Scenario-2-vulnerable_cognito-(Small-or-Moderate).html" target="_blank">CloudGoat Scenario 2: vulnerable_cognito (Small / Moderate): WalkThrough and Mitigation</a>

### _`$ cat /var/www/html/redirect/index.html`_

View my blogs on other platforms:
1. <a href="https://soumyani1.medium.com/aws-threat-detection-series-mitre-att-ck-style-execution-part-2-78f3293f44d6" target="_blank">AWS Threat Detection Series — MITRE ATT&CK Style — Execution (Part 2)</a>
2. <a href="https://soumyani1.medium.com/aws-threat-detection-with-stratus-redteam-series-mitre-att-ck-style-execution-part-1-53a434e152c4" target="_blank">AWS Threat Detection Series — MITRE ATT&CK Style — Execution (Part 1)</a>
3. <a href="https://soumyani1.medium.com/aws-threat-detection-with-stratus-redteam-series-mitre-att-ck-style-initial-access-f1b769878603" target="_blank">AWS Threat Detection Series — MITRE ATT&CK Style — Initial Access</a>
4. <a href="https://aws.plainenglish.io/my-journey-to-learning-soc-part-3-af5039fcf971" target="_blank">My Journey to Learning ThreatHunting: Part 3 - Detection AWS related attacks and events via Splunk - (Part 1/5)</a>
5. <a href="https://soumyani1.medium.com/my-journey-to-learning-soc-part-2-9dd5a40cc08d" target="_blank">My Journey to Learning ThreatHunting: Part 2 - Honing my KQL based detection Engineering</a>
6. <a href="https://soumyani1.medium.com/my-journey-to-learning-soc-part-1-02af20874625" target="_blank">My Journey to Learning ThreatHunting: Part 1 - Windows Endpoint Malware Infection detection via Splunk</a> 
7. <a href="https://github.com/reveng007/AWS_Attack_Simulation_Detection_Lab" target="_blank">AWS Attack Simulation and Detection Lab (In-Complete - Covering detailed version of it in medium blogs)</a> 
8. <a href="https://github.com/reveng007/Cloud-CTFs/blob/main/Wiz%20-%20The%20Ultimate%20Cloud%20Security%20ChampionShip/1.%20Perimeter%20Leak.md" target="_blank">The Ultimate Cloud Security Championship - Perimeter Leak (June 2025) by Wiz</a> 
9. <a href="https://github.com/reveng007/Cloud-CTFs/tree/main/Wz-BigIAM-CTF" target="_blank">Big IAM AWS CTF by Wiz</a> 
10. <a href="https://github.com/reveng007/Cloud-CTFs/tree/main/Wiz-cloudhuntinggames-ExifCola" target="_blank">ExfilCola AWS Cloud Hunting CTF by Wiz</a> 
11. <a href="https://web.archive.org/web/20210925182952/https://hackhouse.net/kerberos-deep-dive/" target="_blank">Kerberos Deep Dive</a> (original website is sold, so had to add backup)
12. <a href="https://web.archive.org/web/20211025155302/https://hackhouse.net/knife/" target="_blank">HTB Knife</a> (original website is sold, so had to add backup)
13. <a href="https://soumyani1.medium.com/thm-steel-mountain-mr-robot-themed-windows-machine-88ee446cbef7" target="_blank">THM Steel Mountain MrRobot</a>
14. <a href="https://soumyani1.medium.com/thm-ninja-skills-writeup-ce333d3223f3" target="_blank">THM NinjaSkills</a>
15. <a href="https://github.com/reveng007/TryHackMe/blob/main/The%20Server%20From%20Hell/README.md" target="_blank">THM TheServerFromHell</a>


<a href="https://www.linkedin.com/in/soumyanil-biswas/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://twitter.com/reveng007" target="_blank"><img src="https://img.shields.io/badge/-Twitter-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white" alt="Twitter"></a>
<a href="mailto:soumyanilbiswas2018@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

