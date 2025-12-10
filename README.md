


# Web Application Vulnerability Assessment

A project that identifies common web vulnerabilities (SQL Injection, XSS) using **DVWA** hosted on Docker. The aim is to demonstrate basic vulnerability testing and mitigation techniques.

## Technologies Used:
- DVWA (Docker)
- Nmap

## Setup
1. **Install Docker**: [Docker Installation Guide](https://docs.docker.com/get-docker/)
2. **Run DVWA using Docker**:
   ```bash
   docker run --rm -d -p 80:80 vulnerables/web-dvwa

3. **Access DVWA**: Open `http://localhost` in your browser and log in with the default credentials.

## Reconnaissance
Using **Nmap**, we scanned the web application for open ports and services to gather intelligence on potential attack surfaces.

## Vulnerability Testing
### SQL Injection
Testing SQL Injection vulnerabilities on the DVWA login form.

### Cross-Site Scripting (XSS)
Testing reflected XSS using DVWA’s XSS page.

## Documentation
Refer to the `Simple Web Application Vulnerability Assessment.pdf` for a detailed report of findings and mitigation strategies.
