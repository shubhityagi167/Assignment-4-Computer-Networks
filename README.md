# Assignment-4-Computer-Networks

Submitted By:- Shubhi Tyagi

Roll Number:- 2301730132

Program:- BTech CSE(AI/ML) Section:- B

Course:- Computer Networks Lab

CourseCode: ENCS304

Github link:- [Assignment Link](https://github.com/shubhityagi167/Assignment-4-Computer-Networks)


## 🔹 Overview
This assignment demonstrates the setup of a **DNS Server** using Cisco Packet Tracer and analyzes how domain names are resolved into IP addresses within a local network.

---

## 🔹 Network Design

Devices Used:
- 1 Server (DNS)
- 2–3 PCs
- 1 Switch

Topology:
PCs → Switch → Server

---

## 🔹 IP Configuration

Server:
- IP: 192.168.1.2
- Subnet: 255.255.255.0

PCs:
- IP: 192.168.1.3 / 192.168.1.4 / 192.168.1.5
- Subnet: 255.255.255.0
- DNS: 192.168.1.2

---

## 🔹 DNS Configuration

Records added:

- www.example.com → 192.168.1.2  
- www.google.com → 192.168.1.2  

---

## 🔹 Testing

Ping:
ping www.example.com  
ping www.google.com  

NSLOOKUP:
nslookup www.example.com  
nslookup www.google.com  

Traceroute:
tracert www.example.com  

---

## 🔹 Analysis

Query Time:
- ~1–2 ms (low latency due to same network)

Response Accuracy:
- Domain names resolved correctly

Name Resolution Process:
- User enters domain name  
- Request sent to DNS server  
- Server returns mapped IP  
- Communication established  

---

## 🔹 Key Observations

- DNS converts domain names into IP addresses  
- Proper IP configuration is essential  
- DNS and network connectivity are separate  
- Packet Tracer does not support real internet  

---

## 🔹 Conclusion

DNS server was successfully configured and tested.  
The system accurately resolved domain names with minimal delay, demonstrating effective DNS operation in a local network.

---

## 🔹 Tools Used
- Cisco Packet Tracer
- Command Prompt
