# WIRESHARK-HTTP-LAB
HTTP traffic analysis lab with Wireshark, object extraction and file hashing.
# Wireshark HTTP Traffic Analysis Lab

## Overview

Practical network traffic analysis lab completed using **Wireshark** and a provided PCAP capture.

The objective was to analyze captured network traffic, apply display filters, navigate through packets, follow HTTP streams and extract relevant information from the traffic.

This lab was completed as part of my practical cybersecurity training focused on **SOC / Blue Team operations**.

---

## Objectives

- Understand the structure of a PCAP capture.
- Navigate and inspect individual packets.
- Identify protocols and relevant packet fields.
- Apply Wireshark display filters.
- Reduce network traffic noise using protocol filtering.
- Follow HTTP streams.
- Analyze client/server HTTP communication.
- Extract information from HTTP responses.
- Identify and analyze transferred files.
- Calculate file hashes for identification and investigation.

---

## Tools

- Wireshark
- PCAP / PCAPNG
- Linux terminal
- MD5
- HTTP
- TCP/IP

---

## Investigation Workflow

### 1. PCAP analysis

The investigation started by opening the provided `.pcapng` capture in Wireshark.

The capture contained a large number of packets, making manual analysis impractical.

The first step was therefore to understand the capture and identify relevant traffic.

---

### 2. Packet inspection

Individual packets were inspected using the **Packet Details** pane.

Relevant protocol layers included:

```text
Ethernet II
IPv4
TCP
HTTP
