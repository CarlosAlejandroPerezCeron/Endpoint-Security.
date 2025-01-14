# Endpoint Security with CrowdStrike and OpenVAS

This project presents the implementation of an endpoint security system combining **CrowdStrike Falcon** (commercial EDR) with **OpenVAS (Greenbone Community Edition)** for vulnerability scanning.

## Features
- **Real-time protection** against malware and ransomware.
- **Continuous endpoint monitoring**.
- **Periodic vulnerability scanning** on servers and computers.
- **Alerts and reports** of critical findings.

## Structure
- `config/`: Configuration files (installation scripts for Falcon Sensor, Docker Compose for OpenVAS, etc.).
- `scripts/`: Installation and automation scripts (e.g. `setup_openvas.sh`, `vulnerability_scan.sh`).
- `documentation/`: Installation, usage and security recommendations guides.

## Requirements
- Ubuntu Server 20.04+ (for OpenVAS).
- Docker and Docker Compose (if you want to use containers).
- CrowdStrike Falcon account with console access (license or trial).
- Internet access to update vulnerability definitions.

## Installation Guide
Check out [`documentation/installation.md`](documentation/installation.md) for a step-by-step guide.

## Usage
1. Install and configure the **CrowdStrike Falcon Sensor** on endpoints.
2. Deploy **OpenVAS** for vulnerability scanning (optional: use Docker).
3. Perform regular scans and fix detected vulnerabilities.
4. Adjust CrowdStrike policies based on findings to improve protection.

## License
This project is available under the MIT license. Check out the [LICENSE](LICENSE) file.
