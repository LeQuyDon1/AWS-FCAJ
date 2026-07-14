---
title: "Các bài blogs đã dịch"
date: 2026-07-05
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

Trong chương này, nhóm thực hiện dịch và tổng hợp một số bài viết từ **AWS Architecture Blog** và **AWS Blog**. Các bài viết tập trung vào những chủ đề mới trên nền tảng AWS như bảo mật, kiến trúc hệ thống cho game trực tuyến và Generative AI. Thông qua việc nghiên cứu các bài viết này, người đọc có thể hiểu rõ hơn về cách AWS giải quyết các bài toán thực tế trong doanh nghiệp cũng như ứng dụng các dịch vụ AWS vào các hệ thống hiện đại.

### [Blog 1 - Dual-token Authentication for Nakama Game Servers with Amazon Cognito on AWS](3.1-Blog1/)
Bài viết giới thiệu kiến trúc **Dual-token Authentication** dành cho các máy chủ game sử dụng **Nakama** trên AWS. Nội dung trình bày cách kết hợp **Amazon Cognito** để quản lý danh tính người dùng với **Nakama** để quản lý phiên chơi, đồng thời sử dụng **Amazon CloudFront**, **AWS WAF**, **Application Load Balancer**, **Network Load Balancer** và **Amazon ECS** nhằm xây dựng một hệ thống game có khả năng mở rộng, bảo mật và đảm bảo trải nghiệm đăng nhập liền mạch cho người chơi.


### [Blog 2 - Restricting AWS Management Console Access with Sign-in Resource-based Policies and RCPs](3.2-Blog2/)
Bài viết trình bày tính năng mới của AWS giúp giới hạn quyền truy cập vào **AWS Management Console** dựa trên các mạng đáng tin cậy bằng **Sign-in Resource-based Policies** và **Resource Control Policies (RCPs)**. Ngoài ra, bài viết còn giới thiệu cách kết hợp với **AWS Organizations** và **AWS CloudTrail** để quản lý chính sách bảo mật tập trung, tăng cường khả năng kiểm soát truy cập và hỗ trợ các yêu cầu về kiểm toán, tuân thủ.


### [Blog 3 - AWS GenAIIC Partner Agent Factory – Delivering AI Agents through AWS Marketplace](3.3-Blog3/)
Bài viết giới thiệu **AWS GenAIIC Partner Agent Factory (PAF)** – chương trình hợp tác giữa AWS và các đối tác nhằm xây dựng các **AI Agent** sẵn sàng triển khai trên **AWS Marketplace**. Nội dung tập trung vào việc ứng dụng **Amazon Bedrock**, **Amazon Bedrock AgentCore** và **Strands Agents** để phát triển các giải pháp Generative AI, giúp doanh nghiệp rút ngắn thời gian triển khai, giảm độ phức tạp và nhanh chóng đưa các AI Agent vào môi trường thực tế.