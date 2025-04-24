# SOC Threat Detection & Response Lab

This repository documents the simulation of a modern Security Operations Center (SOC) using Splunk and Ansible to emulate real-world detection, alerting, and automated incident response workflows. It showcases practical capabilities in security monitoring, data analysis, and security automation.

## Table of Contents
- [Project Overview](#project-overview)  
- [Technologies Used](#technologies-used)  
- [Objectives](#objectives)  
- [Key Achievements](#key-achievements)  
- [Skills Demonstrated](#skills-demonstrated)  
- [Recommendations for Future Enhancements](#recommendations-for-future-enhancements)  
- [Repository Structure](#repository-structure)  

## Project Overview
This lab simulates a functional SOC leveraging Splunk for real-time log ingestion and analysis, along with Ansible for automating response actions. It is designed to validate technical proficiency in detecting and responding to security incidents using scalable and realistic tooling.

[Insert Image of SOC Workflow or Splunk Dashboard Here]  

## Technologies Used
- Splunk – Log aggregation, alerting, and dashboarding  
- Ansible – Automated configuration and incident response  
- Wireshark – Packet analysis  
- Linux (Ubuntu) – Host OS for deploying scripts and agents  

## Objectives
- Configure a centralized SOC environment for ingesting and analyzing security data  
- Build real-time Splunk dashboards to visualize trends and detect anomalies  
- Define alert conditions and automate triggers based on identified threats  
- Integrate Ansible for responsive actions based on triggered alerts  

## Key Achievements
- Deployed and configured a fully operational SOC simulation with Splunk Cloud  
- Created three actionable dashboards to monitor failed logins, unusual access times, and geolocation-based anomalies  
- Configured five Splunk alerts to trigger notifications and auto-responses to simulated threats  
- Developed and executed Ansible playbooks that automated containment tasks based on alert outputs  
- Demonstrated full cycle from log ingestion to response execution  

[Insert Image of Splunk Dashboard with Alert Example Here]  

## Skills Demonstrated
- Proficient use of Splunk for threat hunting and visualization  
- Use of regular expressions to normalize and extract data from varied log sources  
- Development of event types and tagging logic for enriched searching  
- Automation of detection-to-response pipelines with Ansible  
- Visualization and reporting of key incident response metrics  

## Recommendations for Future Enhancements
- Integrate threat intelligence feeds to enrich log context and improve correlation  
- Expand automation to include remediation actions beyond containment  
- Incorporate user behavior analytics to identify compromised credentials  
- Add multi-tenant log source simulation to test detection at scale  

## Repository Structure
```
SOC-Threat-Detection-Response/
├── Ansible-Playbooks/  
│   └── playbook_auto_response.yml  
├── Configurations/  
│   └── splunk_inputs.conf  
├── Documentation/  
│   ├── Splunk_Dashboard_Setup.md  
│   └── Event_Types_Tagging_Guide.md  
├── Logs-Samples/  
│   ├── auth_log_sample.log  
│   └── access_combined.log  
├── Splunk-Dashboards/  
│   ├── login_failures_dashboard.xml  
│   └── anomaly_geolocation_dashboard.xml  
├── README.md
```
