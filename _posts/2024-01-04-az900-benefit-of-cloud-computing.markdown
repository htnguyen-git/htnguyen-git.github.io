---
layout: post
title:  "AZ-900: Benefit of cloud computing"
date:   2024-01-14 15:23:16 +0700
categories: az-900 benefit-of-cloud-computing
---

# Benefit of cloud computing

## High availability - thời gian phục vụ
- Why:
	- User cần app của mình có thể chạy 24/7/365
	- Nếu có sự cố xảy ra, thì app có thể tự phục hồi
- Khó khăn: không có một cloud provider nào có thể đạt 100% 
	- Operating system security patches,
	- Application updates,
	- Hardware replacement,
	- Migrating to a new hosting provider,
	- Hardware failure,
	- Network disruptions, 
	- Power outages, 
	- Natural disaster, 
	- Cyber attacks, 
	- Software bugs,...
- How:
	- Redunancy: Hệ thống dự phòng, sao lưu dữ liệu
	- Auto scaling: tự động mở rộng và co lại các tài nguyên theo nhu cầu
	- Fault-tolerant architecture: Kiến trúc cloud đươc thiết kế để chịu lỗi, và tự phục hồi khi xảy ra sự cố

## Scalability - mở rộng
- Why:
	- User muốn sử dụng hiệu quả tài nguyên
	- User muốn khả năng thêm / bớt resource khi cần thiết
- How:
	- Vertical scaling:
		- Còn được gọi là scaling up, scaling down
		- là việc thêm các resouces vào một single server
		- Vd: Tăng bộ nhớ, số CPUs
		- Có giới hạn scaling
		- Không tăng khả năng availability
	- Horizontal scaling
		- Còn được gọi là scaling out hoặc scaling in
		- Là việc thêm nhiều servers vào 1 hệ thống
		- Không giới hạn cho việc scaling
		- Cân bằng tải sẽ phức tạp
		- Có thể tăng khả năng availability
- Thường thấy ở các hệ thống có mức dao động lưu lượng truy cập theo mùa hoặc theo ngày. Ex
	- Black friday của các e commerce websites
	- School registration sẽ tăng cao khi ở đầu học kỳ

## Elasticity - autoscaling
- Why:
	- User muốn hệ thống tự động scale up, scale down, không phải manual scale
- How:
	- Có một hệ thống giám sát số liệu
	- Thêm tài nguyên khi đạt ngưỡng trên (vd:> 80% RAM)
	- Bớt tài nguyên khi đạt ngưỡng dưới (vd : <50% RAM)

## Reliability - tin tưởng
- Why:
	- User muốn hệ thống hoạt động chính xác
	- User muốn hệ thống hoạt động ổn định
	- User muốn hệ thống hoạt động như kỳ vọng
- How:
	- auto scaling
	- multi region deployments
	- data backup and replication
	- health probe and self healing

## Predictability - dự đoán
- Why:
	- User cần biết trước cách sử dụng tài nguyên
	- User cần biết trước hiệu suất, độ tin cậy của hệ thống
- How:
	- Dự báo và điều chỉnh perfomance dựa theo các hành vi của hệ thống
	- Dự báo chi phí 
- What :
	- Auto scaling
	- Load balancing
	- Different instance types, sizes, pricing tiers
	- Cost management tools
	- Api
	- Pricing calculators

## Security - bảo mật
- Why:
	- User không muốn chia sẻ dữ liệu của mình với bất kì ai
	- Cuộc chiến của hacker - security

## Governance
- Why:
	- User muốn hệ thống chạy đúng theo quy tắc, chính sách, policy
	- User muốn tuân thủ các quy định pháp luật, quy tắc kinh doanh
- How:
	- Các tổ chức tự mình thiết lập chính sách, quy trình, công cụ quản lý
	- Các tổ chức tự mình theo dõi và đánh giá các hoạt động

## Manageability
- Why:
	- User cần cách để quản lý applications, cost, perfomance, security,...
- How:
	- Management of the cloud
		- Quản lý cơ sở hạ tầng
		- Templates: Tạo resoure bằng tay, lưu thành templates. Lần sau sử dụng template để tạo resource thay vì tạo bằng tay 
		- Automations:
		- Scaling:
		- Monitoring and alerts: 
		- Self healthing:
	- Management in the cloud
		- Quản lý resources, dịch vụ, chính sách 
		- Web portal
		- Command line interface and scripts
		- APIs
		- Powershell
- What:
	- Azure portal, CLI, Powershell, Cloud shell, REST APIs, ...
	- Consolidated monitoring and alert system (Hệ thống giám sát và cảnh báo tổng hợp)

	
