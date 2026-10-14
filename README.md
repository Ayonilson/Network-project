# Technova Network Configuration and Access Control Project

This project demonstrates the configuration and testing of a departmental network for Technova using Cisco networking tools. It focuses on network connectivity between the IT, Sales, and HR departments, implementing Access Control Lists (ACLs) to restrict selected traffic while maintaining access to essential services such as HTTP and FTP.

## Table of Contents
- [Project Overview](#project-overview)
- [Network Topology](#network-topology)
- [Tools and Technologies](#tools-and-technologies)
- [Configuration Steps](#configuration-steps)
- [Results and Findings](#results-and-findings)
- [Author](#author)

## Project Overview

The purpose of this project was to configure and test a departmental network for Technova, demonstrating network communication and traffic control using Access Control Lists (ACLs).

The project focused on the following objectives:

- Establishing network connectivity between the IT, Sales, and HR departments.
- Configuring and testing IP address assignment for departmental host PCs.
- Verifying connectivity between hosts using the `ping` command.
- Implementing **Access Control Lists (ACLs)** to control traffic between departments.
- Restricting selected network communication while allowing essential services to remain accessible.
- Testing HTTP and FTP connectivity from the Sales department to the IT department.

## Network Topology

The network topology represents a departmental network comprising the **IT, Sales, and HR departments**. The project includes host PCs and an IT department server, with network devices configured to facilitate communication and enforce traffic restrictions.

### Network Components

- **IT Department:** Contains a host PC and a server providing HTTP and FTP services.
- **Sales Department:** Contains a host PC used to test network connectivity and access to IT department services.
- **HR Department:** Contains a host PC used to verify connectivity with the IT department.
- **Network Infrastructure:** Connects the departmental devices and supports network communication and ACL enforcement.

### IP Addressing

The project document includes screenshots showing the IP addresses received by host PCs in each department. However, the individual IP addresses, subnet masks, default gateways, and complete device configurations are not available as readable text in the document.

Refer to the original network topology and IP address screenshots for the exact addressing details.

## Tools and Technologies

- **Cisco Packet Tracer:** For network topology design, device configuration, and connectivity testing.
- **Routers and Network Devices:** For routing traffic between departmental networks and applying access control policies.
- **Host PCs:** For testing IP addressing, connectivity, and access to network services.
- **IP Addressing:** For identifying hosts and enabling communication across the departmental network.
- **Access Control Lists (ACLs):** For filtering network traffic according to configured access rules.
- **Ping Utility (`ping`):** For testing connectivity between departmental hosts.
- **HTTP:** For testing access to the IT department's web service.
- **FTP:** For testing file transfer service connectivity between departments.

## Configuration Steps

1. **Design the Network Topology**
   - Create the departmental network topology for IT, Sales, and HR.
   - Connect the host PCs, network devices, and IT department server as shown in the project diagram.

2. **Configure IP Addressing**
   - Configure or obtain IP addressing for the host PCs in each department.
   - Verify the IP configuration of each host using the appropriate network configuration tools.
   - Refer to the project screenshots for the exact IP addresses assigned to the IT, Sales, and HR PCs.

3. **Test Initial Network Connectivity**
   - Use the `ping` command to test communication between departmental hosts.
   - Verify connectivity from the HR PC to the IT department PC.
   - Record the successful and unsuccessful connectivity tests.

4. **Configure Access Control Lists**
   - Enter the ACL commands documented in the project to control traffic between the Sales and IT departments.
   - Apply the ACL rules to the appropriate network interface or interfaces.
   - Configure the rules to restrict the intended traffic while preserving access to permitted services.

5. **Verify Traffic Restrictions**
   - Attempt to ping the IT department PC from the Sales department PC.
   - Confirm that the ping fails, as shown in the project evidence.
   - Compare the results with the successful connectivity test from the HR department.

6. **Test HTTP Access**
   - Access the HTTP service hosted on the IT department server from the Sales department.
   - Verify that the Sales department can still reach the server through HTTP despite the configured traffic restrictions.

7. **Test FTP Access**
   - Test FTP connectivity from the Sales department to the IT department.
   - Confirm that FTP communication remains functional after applying the ACL rules.

## Results and Findings

The project demonstrated the use of ACLs to control network traffic while maintaining access to selected services.

### Key Results

- **Departmental Connectivity:** The HR PC successfully pinged the IT department PC, demonstrating connectivity between the two hosts.
- **Traffic Restriction:** The ping from the Sales PC to the IT department PC failed, demonstrating the intended restriction on ICMP connectivity.
- **HTTP Access Preserved:** The Sales department remained able to access the HTTP service hosted on the IT department server.
- **FTP Access Preserved:** FTP communication from the Sales department to the IT department continued to work after the ACL configuration.
- **Selective Traffic Control:** The results demonstrated that network access can be restricted for specific types of traffic without necessarily blocking all communication between departments.

### Findings

The observed results illustrate how **Access Control Lists can enforce network traffic policies at a granular level**. A failed ping does not necessarily mean that a destination is entirely unreachable, because other services may remain accessible when their traffic is permitted by the ACL configuration.

The successful HTTP and FTP tests showed that the Sales department could still access the IT department's server services despite the failed ping test.

## Author

**Name:** Aladebo Adeayo  
**Project:** Technova Network Configuration and Access Control Project  
**Project Reference:** `CS-C26-09-EU-008`  
**Date:** 6 October 2026  
**Location:** Lagos, Nigeria

**Areas of Interest:**
- Computer Networking
- Network Configuration and Troubleshooting
- Access Control Lists (ACLs)
- Cybersecurity and IT Security
- Network Traffic Filtering

**GitHub:** https://github.com/Ayonilson  
**Email:** reycoba2@yahoo.com
