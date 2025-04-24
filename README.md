The Code of Cthulhu: Black-Box Penetration Testing Dojo

    A modular, containerized dojo built for training offensive security skills through real-world web application vulnerabilities.

About the Project

The Code of Cthulhu is a black-box penetration testing platform designed for students, ethical hackers, and security professionals to practice and refine their skills in a safe, controlled environment.

Built as part of a bachelor's degree in Cybersecurity at Noroff University College, the project simulates realistic attack scenarios using a containerized web application stack.
Features

    Realistic black-box testing environment

    Modular architecture built with Flask and Docker

    Simulated vulnerabilities including:

        SQL Injection (SQLi)

        Cross-Site Scripting (XSS)

        Cross-Site Request Forgery (CSRF)

        Command Injection

        Brute-force login

        Server-Side Request Forgery (SSRF)

        Business Logic Flaws

        Weak password storage

        Timing attacks

    Configurable and extensible

    Compatible with tools like OWASP ZAP, Burp Suite, Wapiti, and Nessus

Tech Stack

    Python (Flask)

    MySQL

    Docker & Docker Compose

    HTML, CSS, JS (with Jinja2 templates)

    Apache / NGINX (optional reverse proxy)

    Security tools: OWASP ZAP, Wapiti, Nessus

Getting Started
Prerequisites

    Docker & Docker Compose

    Python 3.10+ (if running locally without Docker)

Quick Setup

git clone https://github.com/kjelli421/Code-Of-Cthulhu-dojo.git
cd Code-Of-Cthulhu-dojo
docker-compose up --build

Visit: http://localhost

Log in or register through the web interface to start interacting with the application.
Intended Audience

    Cybersecurity students

    Penetration testers

    CTF participants

    Red team practitioners

    Web application security researchers

To log into a user, check out the db file. 

More informaiton will be added here soon.

Acknowledgements

    Developed by Kjell Morten Gudmestad

    Supervised by Nelson Uto — Noroff University College

    Inspired by OWASP Juice Shop, DVWA, bWAPP, and Mutillidae II
