# SQL-Injection-Lab-PortSwigger
Lab: SQL injection vulnerability in WHERE clause allowing retrieval of hidden data. When the user selects a category, the application carries out a SQL query.
SQL Injection Lab – PortSwigger

Objective

Learn basic SQL Injection by manipulating category parameters.

Tools Used

- Burp Suite
- Firefox
- Kali Linux

Vulnerability

SQL Injection in category parameter.

Payload Used

' OR 1=1--

Steps Performed

1. Opened the lab
2. Intercepted request in Burp Suite
3. Sent request to Repeater
4. Modified category parameter
5. Injected SQL payload
6. Observed response

Result

Successfully retrieved hidden data/products.

Lessons Learned

Learned how SQL Injection works in URL parameters and how Burp Suite Repeater can test payloads.
