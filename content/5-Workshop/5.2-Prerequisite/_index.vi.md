---
title: "Chuẩn bị"
date: 2026-11-03
weight: 2
chapter: false
pre: " <b> 5.2. </b> "
---

#### Yêu cầu

* Tài khoản AWS có [...]
* Region khuyến nghị: [...]
* Công cụ: AWS CLI, Git, [CDK / SAM / Terraform / Docker nếu dùng]

#### Quyền IAM

<!-- Áp dụng least privilege. Không hard-code access key. -->

```json
{
  "Version": "2012-10-17",
  "Statement": []
}
```

#### Chi phí ước tính

[Tóm tắt một dòng. Dự toán đầy đủ ở mục 5.7.]
