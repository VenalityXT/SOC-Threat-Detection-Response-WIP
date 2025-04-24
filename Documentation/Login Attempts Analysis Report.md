# Login Attempts Analysis Report

## Overview

This report analyzes login activity captured from the `secure-2` sourcetype, focusing on the distribution of successful versus failed login attempts. The data was ingested and visualized using Splunk, and the findings are based on all available events within the dataset.

## Visualization Summary

A pie chart was used to display the breakdown of login statuses. The data shows:

- **95% Failed Logins**
- **5% Successful Logins**

This imbalance is visually stark and clearly indicates abnormal login behavior.

## Threat Insight

The overwhelming number of failed login attempts is indicative of potential **brute-force activity**, **credential stuffing**, or widespread misuse of credentials. The unusually low percentage of successful logins suggests:

- Malicious users or bots attempting unauthorized access
- Poorly configured login systems with repeated authentication failures
- Lack of account lockout policies or IP throttling

## Recommendations

Based on this analysis, the following actions are advised:

- **Implement automated alerting** for high rates of failed login attempts per IP or account
- **Introduce rate limiting and account lockout policies** to deter brute-force activity
- **Correlate failed login spikes** with network activity to detect coordinated attacks
- **Monitor user behavior analytics (UBA)** to identify compromised or suspicious accounts
- **Regularly audit authentication systems** for misconfigurations and vulnerabilities

## Conclusion

This login activity analysis serves as a foundation for building stronger authentication security and detection mechanisms. By visualizing this data, SOC analysts can rapidly identify authentication anomalies and prioritize investigation or mitigation.

---

> *This report is part of the SOC Threat Detection & Response Lab project. See the corresponding Splunk dashboard panel titled “Login Success vs Failure” for interactive visualization.*
