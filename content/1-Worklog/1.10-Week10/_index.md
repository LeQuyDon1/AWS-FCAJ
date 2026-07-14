---
title: "Week 10 Worklog "
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives
* Deepen backend security practices and understand identity flows in cloud environments.
* Strengthen AWS Cognito integration and apply token-based authentication.
* Implement secure data handling with DynamoDB (validation, access patterns, indexes).
* Practice API Gateway authorizers, throttling, and rate limiting.
* Start connecting backend functions into a complete end-to-end workflow.

---

### Tasks to be carried out this week

| Day | Task | Start Date | Completion Date | Reference Material |
|-----|------|-------------|------------------|--------------------|
| 2 | Study authentication/authorization flows (JWT, Access Token, ID Token). <br>- Review OWASP API security. | 22/06/2026 | 22/06/2026 | AWS Study Group |
| 3 | Deep dive into **Cognito User Pool** and **Identity Pool**. <br>- Implement login, signup, refresh token flow. | 23/06/2026 | 23/06/2026 | AWS Study Group |
| 4 | Implement **Lambda Authorizer** and attach it to API Gateway routes. <br>- Add permission policies. | 24/06/2026 | 24/06/2026 | AWS Study Group |
| 5 | Strengthen DynamoDB integration: <br>- Add secondary indexes. <br>- Improve validation & error handling. | 25/06/2026 | 25/06/2026 | AWS Study Group |
| 6 | Build end-to-end testing: <br>- Client → API Gateway → Lambda → DynamoDB → Response. | 26/06/2026 | 26/06/2026 | AWS Study Group |

---

### Week 10 Achievements

#### 1. Gained Deeper Understanding of Authentication & Token Security
I learned in detail how JWT tokens work, how access/ID/refresh tokens differ, and how secure authentication is implemented in serverless applications. I also studied common attack vectors in API security and how to mitigate them using best practices.

#### 2. Successfully Implemented Cognito Authentication Flows
This week, I configured Cognito to support signup, login, multi-factor authentication (optional), and token refreshing. I tested these flows using CLI and Postman, ensuring the backend can securely identify and authorize users.

#### 3. Integrated Lambda Authorizer with API Gateway
I created a custom Lambda Authorizer to validate tokens sent from the client. This allowed me to enforce fine-grained access control and protect backend routes from unauthorized access. This step also increased my confidence with IAM policies and API Gateway security layers.

#### 4. Enhanced DynamoDB Architecture Using Secondary Indexes
I implemented Global Secondary Indexes (GSI) to optimize queries and reduce latency for more complex data access patterns. I also improved error handling and input validation to ensure stable and predictable database behavior.

#### 5. Completed End-to-End Backend Workflow Testing
By the end of the week, I completed full request lifecycle testing:  
Client request → API Gateway → Lambda → DynamoDB → API response.  
I verified that authentication, database operations, and serverless execution flow work together smoothly.

#### 6. Improved Overall Backend Code Structure and Maintainability
I refactored Lambda functions to follow cleaner architecture principles, separating business logic, validation, and database operations. This makes future development easier and reduces potential bugs.

---
