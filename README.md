# 🧠 Hypothesis-Driven Threat Hunting Lab

Simulate advanced detection workflows using MITRE TTPs, behavioral signals, and live log telemetry. This repo is built to reflect how mature SOC and detection engineering teams approach adversary emulation, logging analysis, and iterative hunt refinement.

## 🎯 Why This Repo Exists

Too often, hunts are reactive or aimless. This lab is meant to:
- Build **hypotheses based on threat intel and MITRE TTPs**
- Write and refine **queries against logs** like Sysmon and Auditd
- Record **decision trails** and evidence along the way
- Share **modular playbooks** for repeatable hunts

## 📂 Folder Structure

| Folder               | Description |
|----------------------|-------------|
| `hypotheses/`        | Raw and refined hypotheses derived from threat intel and TTP mapping |
| `queries/`           | Sigma rules, KQL, and Auditd/Sysmon queries tested in the lab |
| `hunt-logs/`         | Annotated logs from hunts, including decisions and dead ends |
| `playbooks/`         | Structured, repeatable workflows for hunting specific techniques |
| `docs/`              | Background on detection engineering methodology and frameworks |

## 🛠 Tools
- Sysmon
- Auditd
- Sigma rules
- Windows Event Logs
- KQL (Azure/Sentinel), Elastic DSL, or grep/Augeas for Linux logs

## 📜 Legal
Only analyze data from systems you own or have explicit permission to monitor.


