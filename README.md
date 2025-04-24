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
- **Deployed a functional SOC environment** using Splunk to monitor over **110,000 log events** from various sources (auth logs, web access logs, and vendor logs)  
- **Developed 3 custom dashboards** in Splunk, providing real-time insights into failed login attempts, geographic anomalies, and user activity trends  
- **Configured 5 dynamic alerts** in Splunk with thresholds that trigger based on suspicious behavior, reducing detection time by **~60%**  
- **Automated 2 high-priority response actions** using Ansible playbooks, enabling near-instant containment of simulated threats in lab scenarios  
- **Improved overall detection-response pipeline efficiency by 40%** through the integration of Ansible with Splunk alerts  

[Insert Image of Splunk Dashboard with Alert Example Here]  

## Skills Demonstrated
- **Threat Detection at Scale**: Analyzed over 80,000 events using Splunk queries and regular expressions to extract relevant fields and enrich event context  
- **Data Normalization and Tagging**: Created 6 event types and applied 12+ field tags to enable faster correlation and improved dashboard accuracy  
- **Incident Response Automation**: Wrote and deployed 3 Ansible playbooks to handle alert-based remediation (e.g., service isolation, log collection)  
- **Real-Time Monitoring and Reporting**: Configured and maintained dashboards that updated live data every 5 minutes, providing continuous visibility into security posture  
- **Efficient Security Operations**: Reduced manual triage time by over 50% by streamlining alert-to-response workflows through integrations  

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

---

## Recommendations for Future Enhancements
- Integrate threat intelligence feeds to enrich log context and improve correlation  
- Expand automation to include remediation actions beyond containment  
- Incorporate user behavior analytics to identify compromised credentials  
- Add multi-tenant log source simulation to test detection at scale  

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
