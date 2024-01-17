---
layout: post
title:  "AZ-900: Cloud service types"
date:   2024-01-10 15:30:16 +0700
categories: az-900 cloud-service-types
---

# Cloud service types
## Phân loại
### Infrastructure as a Service (IaaS)
- IaaS Computing : 
	- Là một server (linux, window)
	- Không cài bất kỳ thứ gì
	- Tính tiền theo second
	- Có nhiều lựa chọn: CPU speeds, RAM, optimizations
- IaaS Storage:
	- Ex: Azure storage
	- Can be configured as a data lake
- IaaS networking
	- Ex: virtual networking
	- Không tính phí
### Platform as a Service (PaaS)
- PaaS = IaaS + a service layer
- PaaS Computing:
	- Ex: Azure App Services
	- Chỉ cần upload code và configuaration tới Azure 
	- Không cần quan tâm tới VM
	- Đã bao gồm scaling features, CI/CD, container, staging and devopment environments,...
- PaaS Storage:
	- Ex: Managed Storaged, Azure SQL Database
	- Không cần quan tâm tới VM
- PaaS Networking:
	- Ex: Azure Front Door, Load Balancer, Firewall,..
	- Là những ứng dụng thực hiện các networking tasks
### Software as a Service (SaaS)
- Ex: Office365, OneDrive, Skype
- SaaS là các cloud apps
- Sẵn sàng sử sử dụng, chỉ cần setup và dùng