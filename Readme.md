# NetMonX

**NetMonX** is a powerful, versatile, and essential tool designed for network monitoring, security assessment, and penetration testing. It offers unique advantages that make it indispensable for professionals responsible for securing networks or assessing their vulnerabilities. Below is an overview of why NetMonX stands out, its core functionalities, and how it can be effectively used by penetration testers, security researchers, and attackers.

## Key Features and Advantages of NetMonX

### 1. Advanced Evasion Techniques
NetMonX incorporates sophisticated evasion techniques that allow it to bypass traditional security defenses such as Intrusion Detection Systems (IDS), Intrusion Prevention Systems (IPS), firewalls, and honeypot systems (like canaries). These features are particularly valuable for:

- **Penetration Testers**: NetMonX enables pentesters to simulate advanced attack scenarios without triggering alarms, which helps in providing a more accurate assessment of a network’s security posture.
- **Security Researchers**: Researchers can study how networks and security devices respond to stealthy, sophisticated attacks, enabling them to develop better defensive strategies.
- **Attackers**: (Ethical or otherwise) can use NetMonX to map out and exploit network vulnerabilities while minimizing the risk of detection.

### 2. Comprehensive Network Monitoring
NetMonX provides continuous, real-time monitoring of network activities, with a special focus on tracking MAC addresses. This capability is crucial for:

- **Network Administrators**: Keeping a close watch on all devices connected to the network, including unauthorized or rogue devices.
- **Incident Response Teams**: Quickly identifying anomalies or suspicious behavior that could indicate a security breach.
- **Compliance and Auditing**: Maintaining detailed logs of all network activities to meet regulatory requirements and conduct thorough security audits.

### 3. Real-Time Anomaly Detection
NetMonX’s ability to detect and log anomalies based on MAC address behavior is particularly valuable for:

- **Threat Detection**: Identifying unusual patterns, such as MAC address spoofing, frequent IP changes, or the appearance of new devices, which could indicate a security threat.
- **Proactive Security**: Allowing security teams to respond to potential threats in real-time, minimizing the window of opportunity for attackers.

### 4. Stealthy and Advanced Scanning Capabilities
NetMonX’s wide range of scanning techniques, such as inverse scanning, bad TCP checksum scanning, and covert channel scanning, makes it indispensable for:

- **Network Reconnaissance**: Gathering detailed information about the network’s structure and its devices without alerting security systems.
- **Vulnerability Assessment**: Identifying weaknesses in the network that could be exploited by attackers, enabling proactive remediation.
- **Red Team Operations**: Conducting realistic attack simulations to test the effectiveness of the organization’s defenses.

### 5. Detailed Reporting and Record Keeping
NetMonX excels in logging and reporting all detected activities and anomalies, which is essential for:

- **Forensic Analysis**: Providing a comprehensive log of all network activities that can be analyzed after an incident to determine its cause and impact.
- **Documentation**: Maintaining detailed records for compliance, auditing, and historical reference, ensuring that no crucial data is lost over time.
- **Continuous Improvement**: Using the collected data to improve network security practices and update defensive measures based on real-world threats.

### 6. Customization and Extensibility
NetMonX is designed to be highly customizable, allowing users to tailor its functionality to their specific needs. This is beneficial for:

- **Security Professionals**: Integrating NetMonX with existing security tools or customizing its behavior to suit specific network environments.
- **Developers**: Extending the tool with new scanning techniques, additional features, or integration with other security platforms.
- **Organizations**: Adapting the tool to fit the unique requirements of their security infrastructure, making it a versatile solution for any environment.

## Why Use NetMonX?

### Pentesters (Penetration Testers)
- **Stealthy Network Scanning**: NetMonX performs highly stealthy scans that can bypass traditional security defenses like IDS/IPS, firewalls, and canaries, enabling pentesters to simulate real-world attack scenarios without triggering alarms.
- **MAC Address-Based Reconnaissance**: NetMonX’s ability to monitor MAC addresses in real-time, track wireless devices, and log all detected MACs is invaluable for building a complete picture of the target environment.
- **Anomaly Detection**: Pentesters can leverage NetMonX’s anomaly detection features to identify potential weaknesses or misconfigurations in a network based on unusual MAC address behavior.
- **Comprehensive Reporting**: After a pentest, NetMonX provides detailed reports that document all activities, detections, and potential vulnerabilities, making it easier for pentesters to deliver actionable insights to their clients.

### Security Researchers
- **Advanced Scanning Techniques**: Security researchers can use NetMonX to explore and document how different scanning techniques affect various types of networks and security systems. Techniques like TCP timestamp manipulation, ACK tunneling, and randomized TTL values provide a rich set of data for analysis.
- **Exploration of MAC Address Behavior**: Researchers can study how MAC addresses behave in different environments, particularly how they interact with security devices like firewalls and IDS/IPS.
- **Testing IDS/IPS Effectiveness**: By utilizing NetMonX’s stealth capabilities, researchers can evaluate the effectiveness of various IDS/IPS systems and firewalls. They can document how these systems respond (or fail to respond) to NetMonX’s advanced evasion techniques.
- **Contribution to Threat Intelligence**: The data collected by NetMonX, especially regarding how networks react to certain types of traffic, can be valuable for developing new defensive strategies or improving existing security tools.

### Attackers
- **Evasion of Detection**: Attackers value tools that allow them to conduct reconnaissance and exploitation activities without being detected. NetMonX’s sophisticated evasion techniques, such as bad TCP checksum scanning and covert channel scanning, are particularly useful for avoiding detection by network security devices.
- **MAC Address Spoofing and Manipulation**: Attackers can use NetMonX to monitor MAC addresses and potentially spoof or manipulate them to blend into the network, evade MAC filtering, or impersonate legitimate devices.
- **Network Mapping for Exploitation**: By building a detailed map of all devices on a network, including their MAC addresses, attackers can identify high-value targets (e.g., servers, network devices) and plan their attacks more effectively.
- **Blending with Legitimate Traffic**: The tool’s ability to generate legitimate-looking traffic alongside its scans helps attackers obscure their activities, making it harder for network administrators to distinguish between normal network traffic and malicious activity.

## How NetMonX Keeps Records

### MAC Address Logging
- **Real-Time Detection**: NetMonX continuously detects and logs every MAC address that appears on the network. This logging includes not just the MAC address itself but also associated data such as the IP address, the first time the MAC was seen, and the last time it was detected.
- **Database Storage**: All detected MAC addresses and their associated data are stored in a persistent database. This database is maintained across sessions, allowing NetMonX to recognize previously seen devices and update their records accordingly.
- **New Device Detection**: When a new MAC address is detected—meaning one that hasn’t been logged before—NetMonX logs it as a new device, storing its details and marking the timestamp of when it first appeared.

### Historical Record Maintenance
- **First and Last Seen Timestamps**: For each MAC address, NetMonX keeps track of when it was first detected and when it was last seen. This helps in understanding the presence and activity patterns of devices on the network over time.
- **Change Detection**: If a MAC address is detected on different IP addresses or shows unusual behavior (such as frequent IP changes), NetMonX logs these changes, providing insights into possible network anomalies or misconfigurations.

### Continuous Monitoring
- **Persistent Monitoring**: NetMonX operates continuously, meaning it is always actively monitoring the network and updating its logs in real-time. This continuous operation ensures that no activity goes unnoticed, and all relevant data is captured.
- **Anomaly Detection**: With continuous monitoring, NetMonX can detect anomalies as they occur. For example, if a device suddenly changes its MAC address or appears on multiple IP addresses in quick succession, NetMonX logs these anomalies and can alert the user.
- **Data Retention**: The persistent database allows NetMonX to retain data over long periods, making it possible to analyze trends, review historical activity, and understand the long-term behavior of devices on the network.

## Why Record-Keeping is Important

### Network Security
- **Tracking Unauthorized Devices**: By keeping a continuous log of all detected MAC addresses, NetMonX helps in identifying unauthorized devices that may attempt to connect to the network. This is crucial for maintaining a secure environment.
- **Anomaly Identification**: The historical data allows for the detection of unusual patterns, such as a MAC address moving between different IPs or appearing on the network at odd times. These anomalies could indicate malicious activity or network misconfigurations that need to be addressed.

### Audit and Compliance
- **Historical Records**: Maintaining detailed logs of all network activities is essential for compliance with various security standards and regulations. NetMonX’s comprehensive record-keeping ensures that organizations have access to the necessary data for audits and compliance checks.
- **Incident Response**: In the event of a security incident, having a detailed log of all network activities, including MAC address movements, can be invaluable for investigating the breach and determining the root cause.

## Conclusion: Why Use NetMonX?

- **Versatility**: Whether you’re a network administrator, security researcher, penetration tester, or ethical hacker, NetMonX offers tools and features tailored to your needs.
- **Advanced Capabilities**: The tool’s ability to perform stealthy, advanced scans, and its focus on MAC address monitoring and anomaly detection, make it stand out as a comprehensive security solution.
- **Proactive Security**: By providing continuous monitoring, real-time detection, and detailed reporting, NetMonX helps you stay ahead of potential threats and maintain a secure network environment.

NetMonX is essential for anyone serious about maintaining robust network security, conducting thorough penetration tests, or studying advanced network behaviors. It’s a tool that not only helps identify vulnerabilities but also enables proactive defense strategies, ensuring that your network remains secure against sophisticated threats.

## Advantages for Pentester/Attacker:

# Confuse Channel:
- Evades detection by exploiting unmonitored channel hopping.
- Verified: Cisco Aironet 2800 Series, Aruba Instant APs (e.g., IAP-305).

# Smuggle Data (ICMP):
- Can discreetly transport data through less scrutinized ICMP traffic.
- Verified: Palo Alto Networks PA-Series Firewalls, Fortinet FortiGate 60F.

# Tunnel Data (DNS):
- Effective for covert communication using DNS queries.
- Verified: Cisco Umbrella, Infoblox DNS Security.

# Wrap Protocol (HTTP):
- Can bypass basic systems by hiding data within HTTP requests.
- Verified: F5 Networks BIG-IP, Imperva Incapsula.

# Fragment Data:
- Potentially avoids detection through fragmented packets.
- Verified: Check Point R81, Juniper SRX Series.

# Steganography:
- Conceals data within other files or protocols, evading simpler systems.
- Example Tools: OpenStego, Steghide.

# Disguise Traffic:
- Converts traffic between OSI layers to obscure its nature.
- Verified: Radware AppWall, Sophos XG Firewall.

## Usages

```bash
General Command Structure

1. Monitoring MAC Addresses

Real-Time Monitoring with Wireless MAC Address Recording
python NetMonX.py monitor start --mac --wireless --record-new

Only Monitor Wireless MAC Addresses
python NetMonX.py monitor start --wireless

2. Security Features
Enable Rogue Device Detection and Anomaly Detection
python NetMonX.py security protect --rogue-detection --anomaly-detection

Enable Stealth Mode for Monitoring
python NetMonX.py security protect --stealth

3. Advanced and Stealthy Scanning
Perform an Inverse Scan with IP Spoofing, Fragmentation, and Stealth Techniques
python NetMonX.py scan start --ip-range 192.168.1.0/24 --technique inverse --spoof-ip 192.168.1.100 --fragment --stealth --randomize --legit-traffic

Perform a Bad TCP Checksum Scan with Fragmentation and Legitimate Traffic
python NetMonX.py scan start --ip-range 192.168.1.0/24 --technique bad-tcp --fragment --legit-traffic --randomize

Perform a Covert Channel Scan with Protocol Obfuscation
python NetMonX.py scan start --ip-range 192.168.1.0/24 --technique covert --stealth --fragment --spoof-ip 192.168.1.200

Perform an ACK Tunneling Scan with Randomized TTL
python NetMonX.py scan start --ip-range 192.168.1.0/24 --technique ack-tunneling --randomized-ttl --fragment --stealth

4. Alerts and Notifications
Configure Email and SMS Alerts
python NetMonX.py alerts configure --email your_email@example.com --sms +1234567890

5. Reporting
Generate a Report for Specific Date Range
python NetMonX.py report generate --start-date 2024-08-01 --end-date 2024-08-10 --output report.txt

6. Device Identification
Identify Device by MAC Address
python NetMonX.py device identify --mac AA:BB:CC:DD:EE:FF

7. Database Management
Initialize the MAC Address Database
python NetMonX.py db manage --init

Add Monitoring Data to the Database
python NetMonX.py db manage --add-data

8. Advanced Network Features
Enable Deep Packet Inspection and Anomaly Detection
python NetMonX.py advanced features --dpi --anomaly-detection

Explanation of Key Options:
--fragment: Fragments packets to bypass detection by some firewalls and IDS/IPS systems.
--spoof-ip: Spoofs the source IP address to avoid detection or attribution.
--stealth: Activates enhanced stealth techniques, modifying packet headers and timing to evade detection.
--randomize: Randomizes the timing of packet sends to avoid detection by timing analysis.
--legit-traffic: Generates legitimate traffic to blend in with normal network activity, making the scan less suspicious.
--randomized-ttl: Randomizes the Time-To-Live (TTL) value to evade detection by systems monitoring for unusual TTL values.

Practical Scenarios:

Bypassing an Advanced Firewall (e.g., Palo Alto PA-220)
- The use of IP spoofing, fragmentation, and stealth techniques can help evade DPI and anomaly detection features of high-end firewalls.
python NetMonX.py scan start --ip-range 10.0.0.0/24 --technique syn-ack --spoof-ip 10.0.0.100 --fragment --stealth --randomize

Evading IDS/IPS Systems (e.g., Snort, Suricata)
- Combining techniques like covert channel scanning, ACK tunneling, and randomized TTL can help bypass signature-based detection and heuristic analysis.

python NetMonX.py scan start --ip-range 172.16.0.0/24 --technique covert --spoof-ip 172.16.0.200 --fragment --randomize --legit-traffic --stealth
Evading Endpoint Protections (e.g., Linux Ubuntu 20.04, macOS Big Sur)

Advanced packet crafting, such as TCP timestamp manipulation and bad TCP checksum scans, combined with protocol obfuscation, can be used to bypass host-based defenses.
python NetMonX.py scan start --ip-range 192.168.1.0/24 --technique tcp-timestamp --frag
```

## Output/Practical Cases
```bash

1. Snort (Configured and Managed Version)
python NetMonX.py scan start --ip-range 172.16.0.0/24 --technique covert --spoof-ip 172.16.0.200 --fragment --randomize --legit-traffic --stealth

2024-08-10 15:30:12 - INFO - Starting covert scan on IP range: 172.16.0.0/24
2024-08-10 15:30:12 - INFO - Spoofing IP: 172.16.0.200
2024-08-10 15:30:12 - INFO - Sending disguised UDP packets with covert data to 172.16.0.1...
2024-08-10 15:30:12 - INFO - Legitimate DNS queries generated for camouflage...
2024-08-10 15:30:14 - INFO - No response from 172.16.0.1 - possibly filtered or closed.
2024-08-10 15:30:16 - INFO - Sending disguised UDP packets with covert data to 172.16.0.2...
2024-08-10 15:30:16 - INFO - Legitimate DNS queries generated for camouflage...
2024-08-10 15:30:18 - INFO - No response from 172.16.0.2 - possibly filtered or closed.
2024-08-10 15:30:20 - INFO - Covert channel scan completed without detection.
2024-08-10 15:30:20 - INFO - Snort system evasion successful, no alerts triggered.

2. Palo Alto PA-220
python NetMonX.py scan start --ip-range 10.0.0.0/24 --technique syn-ack --spoof-ip 10.0.0.100 --fragment --stealth --randomize

2024-08-10 15:45:30 - INFO - Starting SYN+ACK scan on IP range: 10.0.0.0/24
2024-08-10 15:45:30 - INFO - Spoofing IP: 10.0.0.100
2024-08-10 15:45:31 - INFO - Fragmenting packets to evade detection...
2024-08-10 15:45:31 - INFO - Sending SYN+ACK packet to 10.0.0.1 with randomized TTL and sequence number...
2024-08-10 15:45:33 - INFO - No response from 10.0.0.1 - possibly firewalled.
2024-08-10 15:45:34 - INFO - Sending SYN+ACK packet to 10.0.0.2 with randomized TTL and sequence number...
2024-08-10 15:45:36 - INFO - No response from 10.0.0.2 - possibly firewalled.
2024-08-10 15:45:37 - INFO - SYN+ACK scan completed with stealth and fragmentation.
2024-08-10 15:45:37 - INFO - Palo Alto firewall evasion successful, no DPI alerts triggered.
```
