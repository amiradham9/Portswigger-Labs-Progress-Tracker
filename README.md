# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-0-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--00--00-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-0%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 2 of 61
- **Practitioner**: 7 of 174
- **Expert**: 0 of 39

## Categories Covered

- **Authentication vulnerabilities**: 0/14 lab
- **SQL injection**: 9/18 lab
- **Access control**: 0/13 lab

## Notes
- **Full Writeups**: Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
- **Tools Used**: Burp Suite

## How to Read
- **Columns**: 
  - `No`: Sequential lab number.
  - `Date`: When I solved it (YYYY-MM-DD).
  - `Topic`: Vulnerability category (e.g., API Testing, XSS).
  - `Lab Title`: Exact name from PortSwigger.
  - `Difficulty`: Apprentice, Practitioner, or Expert.
  - `Writeup Link`: Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date       | Topic          | Lab Title                                   | Difficulty  | Writeup Link |
|----|------------|----------------|---------------------------------------------|-------------|--------------|
| 1  | 2026-06-15 |SQL injection     |SQL injection vulnerability in WHERE clause allowing retrieval of hidden data  |Apprentice  | N/A |
| 2  | 2026-06-15 |SQL injection     |SQL injection vulnerability allowing login bypass  |Apprentice  | N/A |
| 3  | 2026-06-17 |SQL injection     |SQL injection UNION attack, determining the number of columns returned by the query  |PRACTITIONER  | N/A |
| 4  | 2026-06-17 |SQL injection     |SQL injection UNION attack, finding a column containing text  |PRACTITIONER  | N/A |
| 5  | 2026-06-17 |SQL injection     |SQL injection UNION attack, retrieving data from other tables  |PRACTITIONER  | N/A |
| 6  | 2026-06-18 |SQL injection     |SQL injection UNION attack, retrieving multiple values in a single column  |PRACTITIONER  | N/A |
| 7  | 2026-06-18 |SQL injection     |SQL injection attack, querying the database type and version on Oracle  |PRACTITIONER  | N/A |
| 8  | 2026-06-19 |SQL injection     |SQL injection attack, listing the database contents on non-Oracle databases  |PRACTITIONER  | N/A |
| 9  | 2026-06-19 |SQL injection     |SQL injection attack, listing the database contents on Oracle  |PRACTITIONER  | N/A |
| 10 | 2026-06-23 |Authentication     |Username enumeration via different responses  |Apprentice  | N/A |
| 11 | 2026-06-23 |Authentication     |Username enumeration via subtly different responses  |PRACTITIONER  | N/A |
| 12 | 2026-06-24 |Authentication     |Username enumeration via response timing  |PRACTITIONER  | N/A |
| 13 | 2026-06-24 |Authentication     |Broken brute-force protection, IP block  |PRACTITIONER  | N/A |
| 14 | 2026-06-25 |Authentication     |Username enumeration via account lock  |PRACTITIONER  | N/A |
| 15 | 2026-06-25 |Authentication     |Broken brute-force protection, multiple credentials per request  |Expert  | N/A |
| 16 | 2026-06-25 |SQL injection     |Blind SQL injection with conditional responses  |PRACTITIONER  | N/A |
| 17 | 2026-06-26 |Authentication     |2FA simple bypass  |Apprentice  | N/A |
| 18 | 2026-06-27 |Authentication     |2FA broken logic  |PRACTITIONER  | N/A |
| 19 | 2026-06-27 |Authentication     |Brute-forcing a stay-logged-in cookie  |PRACTITIONER  | N/A |
| 20 | 2026-06-27 |Authentication     |Offline password cracking  |PRACTITIONER  | N/A |
| 21 | 2026-06-27 |Authentication     |Password reset broken logic  |Apprentice  | N/A |
| 22 | 2026-06-27 |Authentication     |Password reset poisoning via middleware  |PRACTITIONER  | N/A |
| 23 | 2026-06-28 |Authentication     |Password brute-force via password change  |PRACTITIONER  | N/A |
| 24 | 2026-07-01 |Path traversal     |File path traversal, simple case  |Apprentice  | N/A |
| 25 | 2026-07-01 |Path traversal     |File path traversal, traversal sequences blocked with absolute path bypass  |PRACTITIONER  | N/A |
| 26 | 2026-07-01 |Path traversal     |File path traversal, traversal sequences stripped non-recursively  |PRACTITIONER  | N/A |
| 27 | 2026-07-03 |Path traversal     |File path traversal, traversal sequences stripped with superfluous URL-decode  |PRACTITIONER  | N/A |
| 28 | 2026-07-03 |Path traversal     |File path traversal, validation of start of path  |PRACTITIONER  | N/A |
| 29 | 2026-07-03 |Path traversal     |File path traversal, validation of file extension with null byte bypass  |PRACTITIONER  | N/A |
| 30 | 2026-07-04 |Command Injection     |OS command injection, simple case  |Apprentice  | N/A |
| 31 | 2026-07-04 |Command Injection     |Blind OS command injection with time delays  |PRACTITIONER  | N/A |
| 33 | 2026-07-05 |Command Injection     |Blind OS command injection with out-of-band interaction  |PRACTITIONER  | N/A |
| 34 | 2026-07-05 |Command Injection     |Blind OS command injection with out-of-band data exfiltration  |PRACTITIONER  | N/A |
| 35 | 2026-07-10 |Business logic     |Excessive trust in client-side controls  |Apprentice  | N/A |
| 36 | 2026-07-10 |Business logic     |High-level logic vulnerability  |Apprentice  | N/A |
| 37 | 2026-07-10 |Business logic     |Low-level logic flaw  |PRACTITIONER  | N/A |
| 38 | 2026-07-11|Access Control     |Unprotected admin functionality  |Apprentice  | N/A |
| 39 | 2026-07-11|Access Control     |Unprotected admin functionality with unpredictable URL  |Apprentice  | N/A |
| 40 | 2026-07-11|Access Control     |User role controlled by request parameter  |Apprentice  | N/A |
| 41 | 2026-07-11|Access Control     |User role can be modified in user profile  |Apprentice  | N/A |
| 42 | 2026-07-12|Access Control     |URL-based access control can be circumvented  |PRACTITIONER  | N/A |
| 43 | 2026-07-12|Access Control     |Method-based access control can be circumvented  |PRACTITIONER  | N/A |
| 44 | 2026-07-12|Access Control     |User ID controlled by request parameter  |Apprentice  | N/A |
| 45 | 2026-07-12|Access Control     |User ID controlled by request parameter, with unpredictable user IDs  |Apprentice  | N/A |
| 46 | 2026-07-12|Access Control     | User ID controlled by request parameter with data leakage in redirect   |Apprentice  | N/A |
| 47 | 2026-07-17|File upload     | Remote code execution via web shell upload   |Apprentice  | N/A |
| 48 | 2026-07-17|File upload     | Web shell upload via Content-Type restriction bypass   |Apprentice  | N/A |
| 49 | 2026-07-17|File upload     | Web shell upload via path traversal   |PRACTITIONER  | N/A |
| 50 | 2026-07-18|File upload     | Web shell upload via extension blacklist bypass   |PRACTITIONER  | N/A |
| 51 | 2026-07-18|Access Control     | User ID controlled by request parameter with password disclosure   |Apprentice  | N/A |
| 52 | 2026-07-18|Access Control     | Insecure direct object references   |Apprentice  | N/A |
| 53 | 2026-07-18|Access Control     | Multi-step process with no access control on one step    |PRACTITIONER  | N/A |
| 54 | 2026-07-18|Access Control     | Referer-based access control    |PRACTITIONER  | N/A |
| 55 | 2026-07-21|Race conditions    | Limit overrun race conditions    |Apprentice  | N/A |
| 56 | 2026-07-21|Race conditions    | Bypassing rate limits via race conditions    |PRACTITIONER  | N/A |
| 57 | 2026-07-23|Race conditions    | Multi-endpoint race conditions    |PRACTITIONER  | N/A |
| 58 | 2026-07-23|Race conditions    | Single-endpoint race conditions    |PRACTITIONER  | N/A |
| 59 | 2026-07-25|XXE Injection    | Exploiting XXE using external entities to retrieve files    |Apprentice  | N/A |
| 60 | 2026-07-25|XXE Injection    | Exploiting XXE to perform SSRF attacks    |Apprentice  | N/A |
| 61 | 2026-07-25|XXE Injection    | Exploiting XInclude to retrieve files    |PRACTITIONER  | N/A |
| 62 | 2026-07-25|XXE Injection    | Exploiting XXE via image file upload    |PRACTITIONER  | N/A |
| 63 | 2026-07-26|XXE Injection    | Blind XXE with out-of-band interaction    |PRACTITIONER  | N/A |
| 64 | 2026-07-26|XXE Injection    | Blind XXE with out-of-band interaction via XML parameter entities    |PRACTITIONER  | N/A |
| 65 | 2026-07-30|Server-side request forgery    | Basic SSRF against the local server    |APPRENTICE  | N/A |
| 66 | 2026-07-30|Server-side request forgery    | Basic SSRF against another back-end system    |APPRENTICE  | N/A |
| 67 | 2026-08-02|Server-side request forgery    | SSRF with blacklist-based input filter    |PRACTITIONER  | N/A |
| 68 | 2026-08-02|Server-side request forgery    | Basic SSRF against another back-end system    |PRACTITIONER  | N/A |
| 69 | 2026-08-02|Cross-site scripting    | Stored XSS into HTML context with nothing encoded    |APPRENTICE  | N/A  |
| 70 | 2026-08-02|Cross-site scripting    | DOM XSS in document.write sink using source location.search    |APPRENTICE  | N/A  |
| 71 | 2026-08-10|API testing    | Exploiting an API endpoint using documentation    |APPRENTICE  | N/A |
| 72 | 2026-08-10|API testing    | Finding and exploiting an unused API endpoint    |PRACTITIONER  | N/A |
| 73 | 2026-08-10|API testing    | Exploiting a mass assignment vulnerability    |PRACTITIONER  | N/A |
| 74 | 2026-08-12|Cross-site scripting    | DDOM XSS in innerHTML sink using source location.search    |APPRENTICE  | N/A  |
| 75 | 2026-08-12|Cross-site scripting    | Reflected XSS into HTML context with nothing encoded    |APPRENTICE  | N/A  |
| 76 | 2026-08-15|Cross-site scripting    | Exploiting cross-site scripting to steal cookies    |PRACTITIONER  | N/A  |
| 77 | 2026-08-15|Cross-site scripting    | Exploiting cross-site scripting to capture passwords    |PRACTITIONER  | N/A  |
| 78 | 2026-08-15|Cross-site scripting    | Exploiting XSS to bypass CSRF defenses    |PRACTITIONER  | N/A  |
| 79 | 2026-08-16|Cross-site scripting    | Reflected XSS into HTML context with most tags and attributes blocked    |PRACTITIONER  | N/A  |
| 80 | 2026-08-16|Cross-site scripting    | Reflected XSS into HTML context with all tags blocked except custom ones    |PRACTITIONER  | N/A  |
| 81 | 2026-08-16|Cross-site scripting    | Reflected XSS with some SVG markup allowed    |PRACTITIONER  | N/A  |