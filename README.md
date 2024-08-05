# Vulnerable Web Application Lab

## Introduction

Welcome to the Vulnerable Web Application Lab! This lab is designed to help you understand and exploit common web vulnerabilities. By working through this lab, you will gain hands-on experience with SQL Injection, Cross-Site Scripting (XSS), and Cross-Site Request Forgery (CSRF). These exercises are intended for educational purposes and to enhance your skills in identifying and mitigating web security threats. Please ensure that you use this knowledge responsibly and only on systems where you have explicit permission to conduct security testing.

The lab setup involves creating a simple web application using Flask and MySQL, which contains deliberately introduced vulnerabilities. You will learn how to exploit these vulnerabilities and understand the potential impact of such security flaws in real-world applications. Furthermore, you will also learn about best practices and techniques to mitigate these vulnerabilities and improve the security of web applications.

## Tools Used

- **Python 3.x**
- **Flask**
- **MySQL**
- **Flask-MySQLdb**

## Key Learning

1. **Understanding Web Vulnerabilities:**
   - **SQL Injection:** Learn how attackers can manipulate SQL queries to access or modify data within a database by injecting malicious SQL code.
   - **Cross-Site Scripting (XSS):** Understand how attackers can inject malicious scripts into web pages, which are then executed in the context of another user's browser, leading to data theft or session hijacking.
   - **Cross-Site Request Forgery (CSRF):** Explore how attackers can trick users into performing unintended actions on web applications where they are authenticated, leading to unauthorized actions.

2. **Exploiting Vulnerabilities:**
   - Perform practical exploitation of these vulnerabilities, observing the consequences and understanding the methods attackers use to leverage these weaknesses.

3. **Mitigation Strategies:**
   - **SQL Injection:** Implement parameterized queries and prepared statements to prevent the inclusion of malicious code in SQL queries.
   - **XSS:** Sanitize and encode user inputs to prevent the execution of malicious scripts.
   - **CSRF:** Utilize CSRF tokens to validate the origin of requests and ensure they come from trusted sources.

4. **Best Practices:**
   - Always validate and sanitize user inputs.
   - Implement proper authentication and authorization checks.
   - Use security libraries and frameworks that help prevent common vulnerabilities.

## Reference

For a detailed walkthrough of the lab, including setup, exploitation steps, mitigation strategies, and key learnings, please refer to the [Vulnerable Lab Walkthrough](https://github.com/surbhibhat22/Web_Vulnerable_HomeLab/blob/300793f3c268bd82cc1678da62d0cf791a595983/Vulnerable_HomeLab.pdf).
