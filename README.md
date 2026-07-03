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