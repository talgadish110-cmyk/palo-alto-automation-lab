# Palo Alto Automation & SecOps Lab 🛡️

## Overview
This project is an automation lab designed for Palo Alto Networks Firewalls and security scripts. It integrates network management, Python automation, and modern DevOps CI/CD pipelines to ensure robust security checks.

## Project Structure 📁
- `scripts/`: Contains automation and validation Python scripts (e.g., `firewall_checker.py`).
- `configs/`: Reserved for network configuration files and firewall rules.
- `.github/workflows/ci.yml`: Automated CI/CD pipeline for syntax checks and code validation.

## Key Features 🚀
- **Target Connection:** Validates connectivity and status against Palo Alto management IP (`192.168.1.254`).
- **DevOps Integration:** Uses GitHub Actions to automatically run python compilation and syntax validation on every push and pull request.
- **Security Best Practices:** Structured with proper Linux permissions and modular script design.

## Author
**Tal Gadish**
