+++
title = "Gsma Cnic Peering"
date = "2024-04-12T11:38:41+01:00"
author = ""
authorTwitter = "" #do not include @
cover = ""
tags = ["", ""]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
color = "" #color from the theme settings
full_screen = true
weight = 1

+++

# Peering Policy

## Introduction

Welcome to our peering policy page. This document outlines the guidelines and requirements for establishing peering connections with our network.

## Guidelines

- **Eligibility:** Peering requests are evaluated based on specific criteria.
- **Technical Requirements:** Peering partners must meet certain technical requirements.
- **Routing Policies:** Our routing policies and procedures are outlined here.
- **Contact Information:** Contact details for peering inquiries.

## CentralNic Registry GRX Bilateral Peering Policy

## 1. Definitions

Terms used in this Peering Policy that are not defined below or in the Agreement are defined in the context in which they are used and have the meanings there stated, and:

- **Autonomous System**: A connected group of one or more IP prefixes run by one or more network operators, which has a single and clearly defined routing policy.
- **Border Gateway Protocol (BGP)**: Standard(s) for inter-Autonomous System routing protocol(s) as recommended now or in the future by the Internet Engineering Task Force (“IETF”).
- **Explicit Route**: A route that covers only a strict, limited subset of all possible destinations.
- **Interconnection Point**: Any interconnection point, public or private, at which the parties agree to connect their respective Networks under this Policy. A description of all Interconnection Points is set forth on Schedule 1 attached hereto and incorporated by this reference, and Schedule 1 shall be amended in writing only by mutual agreement of the parties in the event of any changes.
- **Internet Protocol (IP)**: Networking protocols and procedures, used to provide communication across interconnected networks, that meet the definition of Internet Standards as agreed upon by the Network Working Group of the Internet Architecture Board (“IAB”) and the IETF.
- **Internet Service Provider (ISP)**: A seller of public Internet access and connectivity services operating a Network.
- **Network**: A communications network running IP.
- **CentralNic**: CentralNic, a limited liability company with a principal place of business at Saddlers House, 44 Gutter Ln, London EC2V 6BR.
- **Route of Last Resort (default route)**: A route directing traffic for which no explicit route exists.
- **Third Party**: Any party other than Customer or CentralNic.
- **Third Party Transit Services**: The use of an ISP’s Network to transport traffic between or among two or more destinations, where neither of those destinations is a customer of that ISP.

# Peering Policy

## 2. Introduction

This Peering Policy describes and defines the minimum criteria that CentralNic has established for providing the interconnection between the CentralNic Networks and other Internet Networks in the various regions of the world.

## 3. Connectivity and Network Peering Requirements

### 3.1 Exchange of IP Traffic

The parties agree to exchange IP traffic using BGP between their respective Networks at Interconnection Points that shall have been agreed upon by the parties in writing (including, without limitation, by email).

### 3.2 BGP Version and Connectivity

The parties agree to maintain a current BGP version. Each party shall provide, at its own expense, a connection from its Network to the Interconnection Points hereunder. Each party shall bear the cost of the termination equipment at the end of its connection to the Interconnection Points.

### 3.3 Traffic Restrictions

Each party agrees not to restrict traffic flowing through the Interconnection Points to and from the other party based on the subject matter of the traffic, unless required to do so by an appropriate regulation, order, or similar action of a court, regulatory or governmental agency of competent jurisdiction.

### 3.4 Prohibition of Third Party Transit Services

Use of the other party’s Network for Third Party Transit Services (the use of one party’s network to transport traffic between or among two or more destinations, where neither of those destinations is a customer of that party) is strictly prohibited under this Policy.

### 3.5 Minimum Interconnection Points

Interconnection at a minimum of two (2) diverse peering points.

### 3.6 Routing Configuration

CentralNic reserves the right to modify the routing configuration in coordination with the Peer as necessary in order to improve routing between the CentralNic and Peer networks.

# Peering Policy

## 6. Customer Relations and Administration

### 6.1 Communication with Customers

Each party shall be responsible for communicating with its own customers with respect to its Network. However, nothing in this Section shall be interpreted as limiting in any way the ability of either party to engage in confidential discussions with customers of the other party hereto or as requiring notification thereof to the other party.

### 6.2 Traffic Screening

Each party shall be responsible to screen the traffic of its own customers not desiring public Internet access from distribution across the Interconnection Point(s).

### 6.3 Pricing and Charges

Each party shall independently establish the charges to its own customers for the services provided in connection with this Policy.

## 7. Customer Transmitted Data

### 7.1 Data Monitoring

Except for data required for traffic analysis and traffic control being examined in order for the parties to operate their respective Network, neither party shall monitor the content of any data or other traffic of the other party, which passes through the Interconnection Point(s).

### 7.2 Network Modification

Neither party shall modify its Network infrastructure or Interconnect Point(s) in any way to examine any data of the other party, unless required to do so by an appropriate regulation, order, or similar action of a court, regulatory or governmental agency of competent jurisdiction.

### 7.3 Data Sharing with Third Parties

Except as otherwise agreed between the parties in writing, or upon reasonable written notice and in order to comply with an appropriate regulation, order or similar action of a court, regulatory or governmental agency of competent jurisdiction, neither party shall provide to Third Parties any statistical information derived from data or other traffic of the other party itemized by service provider, by company, or by IP address; provided, however, that each party may provide any of its customers with the customer’s own statistical data, and each party may use such data for projecting future capacity needs.

## 8. Limitation on Services

This Policy shall apply only to IP traffic passing between the parties’ respective Networks. Virtual private data network services and services involving protocols other than the Internet protocols are not covered by this Policy. Neither party shall be entitled or required to carry traffic hereunder if doing so would conflict with any condition imposed by an agreement between the other party and any third party with whom the other party connects.


## 9. Regulatory Approval.
In the event that this Policy, or any of the terms hereof, becomes subject to regulatory approval by any regulatory authority in any jurisdiction including any local, state or federal agencies, the parties shall cooperate, to the extent reasonable and lawful, in providing such information as is necessary to complete any required filing.



# APPENDIX 1: Technical Data

The Peering Policy of both parties is dependent on (a) the following parameters in respect of CentralNic and (b) the parameters set out in the GSMA Root DNS Service Agreement in respect of Customer.

### Technical Contact details

Address: Saddlers House, 44 Gutter Ln, London EC2V 6BR
Phone: 020 3388 0600
Email (General):
Email (Peering):
Slack:

### ASN: 
- **11111**
### TSIG: 
- Required for XFR

### PoP's:
- **AMS_1:**
  - Location: Netherlands
  - Notes: 
  - **NS-1**
     - GRX IP: 1.1.1.1
     - Networks: 2.2.2.2
  - **NS-2**
     - GRX IP: 1.1.1.2
     - Networks: 2.2.2.2
- **AMS_2:**
  - Location: Netherlands
  - Notes: 
  - **NS-3**
     - GRX IP: 1.1.1.1
     - Networks: 2.2.2.2
  - **NS-4**
     - GRX IP: 1.1.1.2
     - Networks: 2.2.2.2
- **SGX:**
  - Location: Singapore
  - Notes: 
  - **NS-5**
     - GRX IP: 1.1.1.1
     - Networks: 2.2.2.2
  - **NS-6**
     - GRX IP: 1.1.1.2
     - Networks: 2.2.2.2
- **IAD:**
  - Location: Ashburn
  - Notes: 
  - **NS-7**
     - GRX IP: 1.1.1.1
     - Networks: 2.2.2.2
  - **NS-8**
     - GRX IP: 1.1.1.2
     - Networks: 2.2.2.2


     {{< code language="css" title="Really cool snippet" id="1" expand="Show" collapse="Hide" isCollapsed="true" >}}
test
{{< /code >}}
