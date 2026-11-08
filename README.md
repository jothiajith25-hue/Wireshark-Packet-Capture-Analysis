# Wireshark Packet Capture Analysis

## Objective
To analyze a sample network packet capture using Wireshark and understand DNS queries and HTTP requests.

## Tool Used
- Wireshark

## Sample Capture Details
- File: `synthetic.pcap`
- Total packets: 2
- Source IP: `192.0.2.10`
- Destination IP: `192.0.2.20`

## 1. DNS Analysis
- Protocol: DNS
- Transport: UDP
- Destination Port: 53
- Requested Domain: `training.example`
- Query Type: A Record

**Observation:** The client sent a DNS query requesting the IPv4 address of `training.example`.

## 2. HTTP Analysis
- Protocol: HTTP
- Transport: TCP
- Destination Port: 80
- Request Method: GET
- Request Path: `/practice`
- Host: `training.example`

**Observation:** The client sent an HTTP GET request to access the `/practice` path on `training.example`.

## Learning Outcome
Through this activity, I learned how to:
- Apply display filters in Wireshark.
- Identify DNS and HTTP packets.
- Inspect source and destination IP addresses.
- Understand DNS queries and HTTP request details.

## Conclusion
The sample packet capture was successfully analyzed using Wireshark. I identified one DNS query and one HTTP GET request. This activity helped me understand basic network traffic analysis.

**Note:** This experiment used a synthetic training capture file and did not involve real user traffic.
