
# Wireshark Packet Analysis Project

## Overview
Analyzed network packet captures across HTTP, DNS, Telnet, and TCP traffic using Wireshark. Applied targeted display filters to identify security issues and documented findings in a structured incident report.

## Files
- Network_Analysis_Report_Vishwaa.pdf — Full incident report with findings and recommendations
- Screenshots — Evidence screenshots from Wireshark analysis

## Tools Used
- Wireshark 4.x
- Sample PCAP files from Wireshark SampleCaptures repository

## Key Findings
- Detected active port scan from IP 10.100.25.14 targeting 10.100.18.12
- Captured cleartext credentials transmitted over Telnet (username and password visible in plaintext)
- Analyzed DNS query patterns across google.com and netbsd.org
- Identified unencrypted HTTP traffic exposing request details

## Skills Demonstrated
- Network packet analysis
- Wireshark display filters
- Threat identification and documentation
- Incident report writing
