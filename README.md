# Wazuh-agentic-ai
An n8n workflow set up to send automatic wazuh alerts to our desired channel (gmail or discord)

In this project, I explored how automation can transform SOC operations into faster, smarter, and more efficient systems.
I built an automated detection pipeline integrating Wazuh SIEM, n8n, and VirusTotal to identify, verify, and report threats in real time.

✨ Core Stack:
✦ Wazuh SIEM: Monitored endpoints and generated security alerts.
✦ n8n: Automated workflow orchestration via webhooks.
✦ VirusTotal API: Verified file hashes (MD5, SHA1, SHA256) for threat intelligence.

✨ How It Works:
When Wazuh detects suspicious file events, it triggers a webhook to n8n. The workflow extracts file hashes, scans them through VirusTotal, and sends automated email alerts for quick response.

✨ This project strengthened my understanding of SIEM integration, SOC automation, and threat intelligence, showing how AI-driven workflows can enhance real-time security operations.
