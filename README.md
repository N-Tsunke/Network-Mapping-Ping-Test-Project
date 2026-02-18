# Network-Mapping-Ping-Test-Project

---

## Project Overview

This project demonstrates applied networking knowledge by mapping a home network, testing connectivity, and analyzing results using TCP/IP concepts.

**Objectives:**

- Map a home network topology
- Identify connected devices and IP configurations
- Test local and internet connectivity using `ping`
- Explain DNS, ICMP, and routing
- Document findings in a professional portfolio format

---

# Part 1: Network Mapping

### Step 1: Identify Connected Devices

Devices in the network environment:

- **Internet**  
- **Wi-Fi Router (Default Gateway):** 172.20.6.1  
- **Computer (IPv4 Address):** 172.20.6.168  

## What It Shows  

* The **Computer (172.20.6.168)** sends and receives data.  
* The **Wi-Fi Router (172.20.6.1)** acts as the default gateway and directs traffic.  
* The **Internet** provides access to external networks and services.  

This shows the full communication path from the computer to the router and then to the internet.

**Screenshot:**  
<img width="543" height="127" alt="Step 2 , Identify IP Address" src="https://github.com/user-attachments/assets/ec3a01ab-601a-45bc-8724-0fc3209bae82" />

## Why It Is Important  

* **Troubleshooting:** Helps identify whether the issue is with the computer, router, or internet connection.  
* **Correct Configuration:** Confirms the correct IP address and default gateway are set.  
* **Network Communication:** Demonstrates how devices communicate within a network.  
* **Security:** Helps detect unknown or unauthorized devices.  

Identifying connected devices ensures proper connectivity, correct configuration, and reliable network performance.

---

### Step 2: Ping Router (`ping-router.png`)

## What It Shows  

Testing connection to your router (internal network).

**Screenshot:**  
<img width="543" height="127" alt="Step 2 , Identify IP Address" src="https://github.com/user-attachments/assets/ec3a01ab-601a-45bc-8724-0fc3209bae82" />

## Key Observations  
* **Reply received:** Confirms the computer can reach the router.  
* **Time (ms):** Shows latency to the router. Lower is better (usually 1–5ms for local networks).  
* **No packet loss:** Indicates a stable internal connection.  

# Interpretation  
* Your local network is working correctly.

---

# Step 3: Ping Google (`ping-google.png`)

## What It Shows  
* Testing connection to the internet.

**Screenshot:**  
<img width="543" height="127" alt="Step 2 , Identify IP Address" src="https://github.com/user-attachments/assets/ec3a01ab-601a-45bc-8724-0fc3209bae82" />

# Key Observations  
* **Reply received:** Confirms that the computer can reach an external server.  
* **Time (ms):** Measures latency to the server (usually 20–50ms for nearby servers).  
* **No packet loss:** Indicates a stable internet connection.  

# Interpretation  
* Your computer has a working internet connection.

---

# Network Diagram (`network-diagram.png`)

## What It Shows  
* A visual layout of the home network.

**Screenshot:**  
<img width="543" height="127" alt="Step 2 , Identify IP Address" src="https://github.com/user-attachments/assets/ec3a01ab-601a-45bc-8724-0fc3209bae82" />

## Components Included  
* Internet Connection  
* Router  
* Computer (172.20.6.168)  

## Why It’s Important  
* Helps visualize how devices are connected.  
* Useful for troubleshooting and documentation.

---

# Project Summary  

By combining IP configuration, ping tests, and a network diagram, this project demonstrates the ability to:

* Identify device network settings  
* Verify internal connectivity (router communication)  
* Verify external connectivity (internet access)  
* Document network layout for troubleshooting or analysis  

---

# Key Learning Outcomes  

* Mapped and documented a home network  
* Verified IP configuration and default gateway  
* Tested connectivity to router and internet  
* Validated DNS functionality  
* Applied TCP/IP and ICMP concepts  
* Interpreted routing and latency results  

---

# Tools Used  

* Windows Operating System  
* Command Prompt  
* Wi-Fi Router  
* Internet Service Provider (ISP)  
* GitHub  

---

# Conclusion  

This project successfully demonstrates practical networking knowledge.

The computer (**172.20.6.168**) successfully communicated with the router (**172.20.6.1**) and accessed the internet, confirming:

* Proper IP configuration  
* DNS resolution  
* Routing functionality  

This assessment reflects applied troubleshooting skills aligned with professional IT support practices


