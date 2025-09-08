# Project-App

## Wep-App Cold Disaster Recovery

Discription
- This document provides a detailed guide for deploying a secure and scalable
AWS infrastructure for a customer-facing application. The architecture
includes networking, firewalls, load balancing, auto scaling, databases,
security monitoring, and disaster recovery (DR).

## Architecture:

<img width="1715" height="739" alt="my-project" src="https://github.com/user-attachments/assets/23f13e40-0bb6-4579-80ea-37495af7991e" />

### Step 1: Network Setup

#### -Migration-VPC
<img width="693" height="363" alt="image" src="https://github.com/user-attachments/assets/29517abe-2f1c-46ce-a8fa-b04ef24416ce" />

#### -Subnets
<img width="1350" height="436" alt="image" src="https://github.com/user-attachments/assets/06adbb2e-4880-4273-a8e7-384cb7e63ab4" />

#### -Route Table
<img width="1345" height="472" alt="image" src="https://github.com/user-attachments/assets/ab8acaa2-3ab2-432f-b432-cb8d0aded6c1" />

### Step 2: Firewall (AWS Network Firewall)

<img width="1365" height="559" alt="image" src="https://github.com/user-attachments/assets/d1c9e117-c375-406b-a8a2-854e10ce5b75" />

<img width="1104" height="249" alt="image" src="https://github.com/user-attachments/assets/edc7c780-23ee-436c-9a88-8c922f2e48f7" />

### Step 3: Migration from On-Prem to AWS

<img width="1365" height="436" alt="image" src="https://github.com/user-attachments/assets/324f08bf-184d-4dfc-ab50-79c497f4c816" />

<img width="1366" height="295" alt="image" src="https://github.com/user-attachments/assets/2ce9135d-81fa-4130-8862-028cb859eb28" />

### Step 4: Application Load Balancer (ALB) + WAF

<img width="1362" height="552" alt="image" src="https://github.com/user-attachments/assets/d2953b75-aecf-4250-b3fa-5a79056e7dc9" />

<img width="1366" height="537" alt="image" src="https://github.com/user-attachments/assets/4e0a29cb-37f1-4c11-8827-f12e88eeb41f" />

### Step 5: Auto Scaling Group (ASG)

<img width="1366" height="552" alt="image" src="https://github.com/user-attachments/assets/0c8de1d8-f5b5-439a-8229-313b3e9e6774" />

### Step 6: Database (Amazon RDS MySQL)

<img width="1366" height="570" alt="image" src="https://github.com/user-attachments/assets/0503a039-85ee-4249-961b-3bdc1975c57c" />

<img width="1251" height="394" alt="image" src="https://github.com/user-attachments/assets/c759580e-2640-491d-92bc-411fc31c2da6" />

### Step 7: Back Up (Same Region)

<img width="1357" height="482" alt="image" src="https://github.com/user-attachments/assets/fd7c0e5d-7eec-48d8-a116-f7c8ad2bcc67" />

### Step 8: Disaster Recovery (DR)

<img width="1352" height="319" alt="image" src="https://github.com/user-attachments/assets/ddb53f7a-38ce-48ed-bdac-b718ace32d4f" />

<img width="1354" height="319" alt="image" src="https://github.com/user-attachments/assets/b65952b3-b9d3-43a4-b63b-6be179c84407" />

### Step 9: Security Feature

#### Guard Duty

<img width="1360" height="374" alt="image" src="https://github.com/user-attachments/assets/e9a7734b-979b-4ef6-9463-2d486110ed96" />


#### Vpc Flow Log

<img width="1125" height="248" alt="image" src="https://github.com/user-attachments/assets/32d854a1-9943-48ce-9d98-47ef7fe801ee" />


#### Cloud Watch

<img width="1363" height="439" alt="image" src="https://github.com/user-attachments/assets/16543af0-6601-4975-ab47-f3aef1f50a7a" />

### Step 10: DNS Resloution (Route 53)

<img width="1364" height="584" alt="image" src="https://github.com/user-attachments/assets/76ae86d0-15aa-4efe-bcb3-52e447dd84c2" />
