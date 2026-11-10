---
title: "Giới thiệu"
date: 2026-11-03
weight: 1
chapter: false
pre: " <b> 5.1. </b> "
---

#### Giới thiệu

[...]

#### Kiến trúc

<!-- Tự vẽ bằng icon chính thức mới nhất của AWS. Hệ thống triển khai thật (production) phải khớp với sơ đồ này. -->
<!-- ![Kiến trúc](/images/5-Workshop/5.1-Workshop-overview/architecture.png) -->

*Hình 1: [Chú thích]*

#### Luồng dữ liệu

1. [...]
2. [...]

#### Các dịch vụ AWS sử dụng

| Dịch vụ | Vai trò trong workshop | Lý do chọn |
| ------- | ---------------------- | ---------- |
| [...] | [...] | [Chi phí / high availability / serverless hay managed] |

#### Well-Architected

| Trụ cột | Thiết kế đáp ứng thế nào |
| ------- | ------------------------ |
| Operational Excellence | [Giám sát, logging, cảnh báo tự động, IaC] |
| Security | [IAM least privilege, không public tài nguyên, không hard-code credentials] |
| Reliability | [Chịu lỗi, retry, event-driven, mở rộng] |
| Performance Efficiency | [...] |
| Cost Optimization | [Free Tier, trả theo lượt dùng, S3 Lifecycle] |
