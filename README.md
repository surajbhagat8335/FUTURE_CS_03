# FUTURE_CS_03
API Security Risk Analysis Report – Cyber Security Internship Task 3
# API Security Risk Analysis Report

## Overview

This project presents an API Security Risk Analysis performed as part of the **Cyber Security Internship Task 3 (2026)**.
The goal of this task is to analyze public API endpoints, identify potential security risks, and document the findings in a professional security report.

Modern applications rely heavily on APIs for communication between services. If APIs are not properly secured, attackers may gain unauthorized access to sensitive data or abuse system functionality.

---

## Objective

The objective of this analysis is to:

* Examine public API endpoints
* Identify potential API security risks
* Analyze authentication and data exposure issues
* Provide security recommendations to improve API protection

---

## Tools Used

The following tools were used during the analysis:

* **Postman** – for testing API endpoints and inspecting responses
* **Browser DevTools** – for examining headers and request behavior
* **JSONPlaceholder Test API** – demo API used for security analysis

---

## API Tested

The public demo API used in this project:

```
https://jsonplaceholder.typicode.com
```

Endpoints analyzed:

```
/users
/posts
/comments
```

These endpoints were tested using GET requests in Postman to inspect responses and identify potential security risks.

---

## Methodology

The following steps were performed during the analysis:

1. Review API documentation
2. Send API requests using Postman
3. Inspect response data and headers
4. Identify potential security risks
5. Document findings and recommendations

Screenshots of API requests and responses were captured as evidence.

---

## Key Security Findings

The analysis identified several potential risks commonly found in insecure APIs:

* **Unauthenticated endpoints** allowing public access to data
* **Excessive data exposure** in API responses
* **Predictable resource identifiers** enabling data enumeration

These risks could lead to unauthorized data access or abuse if found in production systems.

---

## Security Recommendations

To improve API security, organizations should consider:

* Implementing strong authentication mechanisms (API keys, OAuth, JWT)
* Limiting sensitive data exposure in API responses
* Implementing rate limiting to prevent abuse
* Monitoring API traffic for suspicious activity

---

## Project Structure

```
FUTURE_CS_03
│
├── screenshots
│   ├── api_users_endpoint.png
│   ├── api_posts_endpoint.png
│   └── api_comments_endpoint.png
│
├── report
│   └── API_Security_Risk_Analysis_Report.pdf
│
└── README.md
```

---

## Author

Suraj Kumar
Cyber Security Internship – Future Interns (2026)
