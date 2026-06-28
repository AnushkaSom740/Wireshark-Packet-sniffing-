📡 Wireshark Packet Sniffing – Portfolio Activity
1. Project Title
Packet Sniffing & Traffic Analysis using Wireshark

2. Overview
This project demonstrates my ability to capture, analyze, and interpret network traffic using Wireshark. The activity highlights practical skills in packet sniffing, protocol analysis, and identifying suspicious or abnormal traffic patterns.

3. Objectives
Showcase packet sniffing and traffic monitoring skills.

Analyze protocols (TCP, UDP, HTTP, DNS, etc.).

Detect anomalies such as failed connections, unusual IP activity, or potential malicious traffic.

Document findings in a structured and professional format.

4. Tools & Techniques
Wireshark – for packet capture and protocol analysis.

TCPdump – for command-line packet capture (optional).

Applied OSI Model and TCP/IP stack concepts.

Referenced MITRE ATT&CK techniques for suspicious traffic patterns.

5. Methodology
Captured live traffic on a test network using Wireshark.

Applied filters (e.g., ip.addr == x.x.x.x, http, tcp.port == 80).

Examined packet headers and payloads for anomalies.

Identified communication between client and server, including DNS lookups and HTTP requests.

Documented suspicious activity (e.g., repeated failed login attempts, unusual port scanning).

6. Key Findings
Detected abnormal DNS queries to external IP addresses.

Observed repeated TCP SYN packets indicating possible port scanning.

Identified unencrypted HTTP traffic exposing sensitive information.

7. Outcome / Impact
Gained hands-on experience in packet sniffing and traffic analysis.

Strengthened ability to detect anomalies and potential threats.

Improved understanding of how attackers exploit insecure protocols.

8. How to View/Run
Open the .pcap files in Wireshark for detailed traffic analysis.

Use provided filters in the /filters folder to replicate findings.

Refer to analysis_report.pdf for documented results.

9. Future Improvements
Automate packet capture and alerting using Splunk/Chronicle SIEM integration.

Extend analysis to encrypted traffic using TLS decryption (where permitted).

Build dashboards for real-time monitoring.
