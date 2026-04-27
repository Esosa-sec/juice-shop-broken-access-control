# juice-shop-broken-access-control
A vulnerability test on Juiceshop 
## Project: Broken Access Control in OWASP Juice Shop

### Tools Used
- Burp Suite
- Kali Linux

### Vulnerabilities Found
- IDOR (Basket access manipulation)
- Unauthenticated API access

### Exploit
Changed:
GET /rest/basket/6 → /rest/basket/3

### Impact
Accessed other users' data without authorization
