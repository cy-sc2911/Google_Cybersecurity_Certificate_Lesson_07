 🎓 Google Cybersecurity Certificate — Python Labs | Assignments | Lesson 7

---

# 📌 Overview

This repository contains hands-on Python work from the Google Cybersecurity Certificate program — one of the most recognized entry-level certifications in the field. The course covered how Python is used in real security operations: automating tasks, parsing logs, and writing security-focused scripts.

**Certificate:** Google Cybersecurity Professional Certificate
**Platform:** Coursera
**Status:** ✅ Completed

## 🛠️ Skills Demonstrated

| Skill | Application |
|---|---|
| File I/O | Parsing `.log` and `.txt` security files |
| String manipulation | Extracting IPs, usernames, timestamps |
| Conditionals & loops | Automating log review |
| List & dictionary use | Storing and querying security data |

## 📄 Sample Script — List & distionary use

```python
# Creating new entry 'allow_list.txt'
import_file = "allow_list.txt"

ip_addresses = "192.168.218.160 192.168.97.225 192.168.145.158 192.168.108.13 192.168.60.153 192.168.96.200 192.168.247.153 192.168.3.252 192.168.116.187 192.168.15.110 192.168.39.246"

with open(import_file, 'w') as file:
    file.write(ip_addresses)

with open(import_file, 'r') as file:
    text = file.read()
print(text)

# Assign `import_file` to the name of the file 

import_file = "allow_list.txt"

## 🧠 What I Learned

- How Python is used in SOC (Security Operations Center) workflows
- Automating log analysis that would take hours manually
- Writing clean, readable scripts following security best practices
- Applying Python to real-world cybersecurity scenarios

## 🔗 Certificate

[Google Cybersecurity Professional Certificate — Coursera](https://www.coursera.org/account/accomplishments/specialization/GAP2QE1Q1ETY?utm_source%3Dandroid%26utm_medium%3Dcertificate%26utm_content%3Dcert_image%26utm_campaign%3Dsharing_cta%26utm_product%3Ds12n)
