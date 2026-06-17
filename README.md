# Thiết kế và Đánh giá Hiệu năng Mạng cho Trường Đại học

## Tổng quan dự án

Đây là dự án thiết kế và đánh giá hạ tầng mạng cho một trường đại học quy mô vừa, bao gồm các khu vực như giảng đường, phòng thực hành máy tính, khu hành chính, phòng máy chủ, mạng không dây và hệ thống camera giám sát.

Dự án tập trung vào thiết kế mạng logic, thiết kế mạng vật lý, phân chia VLAN, triển khai firewall, Wireless LAN Controller, Access Point, hệ thống giám sát mạng và đánh giá hiệu năng mạng.

## Mục tiêu dự án

- Thiết kế hệ thống mạng ổn định, bảo mật và có khả năng mở rộng.
- Phân chia mạng thành các VLAN riêng biệt cho sinh viên, hành chính, máy chủ, phòng thực hành và thiết bị IoT/camera.
- Tăng cường bảo mật bằng firewall, ACL, Port Security, DHCP Snooping và Dynamic ARP Inspection.
- Triển khai hệ thống mạng không dây bằng WLC và Access Point.
- Giám sát hiệu năng mạng bằng PRTG và SNMP.
- Đánh giá hiệu năng mạng dựa trên độ trễ, mất gói, băng thông, CPU/RAM và trạng thái cảnh báo.

## Vai trò của tôi

- Thiết kế kiến trúc mạng vật lý và mạng logic.
- Lập kế hoạch phân chia VLAN theo từng khu vực chức năng.
- Đề xuất triển khai thiết bị mạng như Access Switch, Core Switch, Firewall, WLC và Access Point.
- Xây dựng sơ đồ topo mạng.
- Chuẩn bị slide thuyết trình kỹ thuật cho dự án.

## Công nghệ và kiến thức sử dụng

- VLAN
- TCP/IP
- DHCP
- DNS
- NAT
- ACL
- OSPF
- Firewall
- Core Switch
- Layer 2 / Layer 3 Switching
- Wireless LAN Controller
- Access Point
- SNMP
- PRTG Network Monitor
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- Network Performance Evaluation

## Điểm nổi bật

- Thiết kế kiến trúc mạng phân cấp ba lớp: Core, Distribution và Access.
- Phân đoạn mạng bằng VLAN để tăng bảo mật và quản lý lưu lượng hiệu quả.
- Tách riêng các vùng mạng dành cho sinh viên, hành chính, máy chủ, phòng thực hành và thiết bị IoT/camera.
- Thiết kế hệ thống có khả năng dự phòng với Core Switch và liên kết dự phòng.
- Quản lý mạng không dây tập trung thông qua WLC và Access Point.
- Giám sát hệ thống bằng PRTG với các chỉ số như độ trễ, mất gói, CPU/RAM và lưu lượng mạng.

## Đánh giá hiệu năng

Hệ thống mạng được đánh giá dựa trên các tiêu chí:

- Độ trễ
- Tỷ lệ mất gói
- Mức sử dụng băng thông
- Mức sử dụng CPU và bộ nhớ
- Lưu lượng trên các cổng mạng
- Trạng thái cảnh báo trên PRTG

## Cấu trúc thư mục

```text
docs/          Báo cáo dự án
diagrams/      Sơ đồ mạng logic và vật lý
configs/       Cấu hình thiết bị mạng
screenshots/   Ảnh chụp kết quả giám sát và kiểm thử
