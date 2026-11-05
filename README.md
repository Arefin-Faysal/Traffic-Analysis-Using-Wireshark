# Network Traffic Analysis Using Wireshark

## Experiment: Comparison of Wi-Fi and Ethernet Network Traffic

### 1. Experiment Overview

This experiment was conducted to observe and compare network traffic using Wireshark over two different network connections while visiting the same website.

The experiment focuses on identifying differences in network packets, protocols, source and destination addresses, and packet transmission behavior.

### 2. Objectives

- Capture network traffic using Wireshark.
- Observe traffic over two different network connections.
- Visit the same website on both networks.
- Compare the captured packets and identify differences.
- Understand how Wireshark helps analyze network communication.

### 3. Tools and Requirements

- Wireshark
- Windows 11
- Internet connection
- Webcam for identity verification

### 4. Experimental Procedure

1. Open Wireshark and select the appropriate network interface.
2. Start capturing network traffic.
3. Visit the same website using the first network connection.
4. Stop the capture and save the screenshot.
5. Repeat the process using the second network connection.
6. Compare the captured packets, protocols, and network information.

### 5. Experimental Results

#### Network 1: Loopback Traffic Capture

The first screenshot shows Wireshark capturing IGMPv2 traffic on the loopback interface.

- Source IP: `192.168.10.150`
- Destination IP: `224.0.0.252` and other multicast addresses
- Protocol: IGMPv2
- Observation: The captured packets are primarily multicast membership reports.

[Network 1 - Loopback Capture]

<img width="1200" height="675" alt="Screenshot 2026-11-05 092911" src="https://github.com/user-attachments/assets/afe81d6a-eca2-4da0-98aa-433afe2891c2" />


#### Network 2: Wi-Fi

The second screenshot shows Wireshark capturing network traffic over a Wi-Fi connection.

- Source IP: `10.89.124.45`
- Destination IPs: Multiple external and local addresses
- Protocols: QUIC, DNS, TCP, and TLSv1.2
- Observation: The capture contains DNS queries, TCP connections, encrypted TLS traffic, and QUIC communication.

[Network 2 - Wi-Fi Capture]

<img width="1200" height="675" alt="Screenshot 2026-11-05 093220" src="https://github.com/user-attachments/assets/475c9b44-3724-4086-9ad7-eb7b876f9181" />

### 6. Comparison

| Feature | Network 1 | Network 2 |
|---|---|---|
| Interface | Loopback | Wi-Fi |
| Main protocols | IGMPv2 | QUIC, DNS, TCP, TLS |
| Traffic type | Multicast membership reports | Web and network communication |
| IP addresses | 192.168.10.150 | 10.89.124.45 |
| Observed behavior | Multicast group membership | DNS resolution and encrypted communication |

**Note:** The first screenshot shows a loopback interface, not an Ethernet interface. Therefore, it should not be considered an Ethernet capture. A separate Ethernet capture is required if the assignment specifically requires Wi-Fi and Ethernet.

### 7. Conclusion

This experiment demonstrated how Wireshark can be used to capture and analyze network traffic across different interfaces.

The Wi-Fi capture showed multiple protocols associated with web communication, including DNS, TCP, TLS, and QUIC. The loopback capture primarily showed IGMPv2 multicast membership reports.

The experiment helped develop practical knowledge of network interfaces, packet analysis, IP addressing, and communication protocols.

### 8. Student Information

- **Name:** MD. Arefin Faysal
- **Student ID:** [Enter Your Student ID]
- **Course:** [Enter Course Name]
- **Experiment:** Network Traffic Analysis Using Wireshark
- **GitHub Repository:** [Paste Your GitHub Repository URL]

### 9. Screenshots

The screenshots contain the required timestamp, student name, student ID, and webcam view for verification.








