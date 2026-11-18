# SSH Automation Testing with Python

Educational project focused on testing and automating remote Linux operations over SSH.

## Focus

- Python-based remote command execution
- SSH connectivity
- Paramiko
- Automated validation of command results
- Basic deployment and remote test scenarios

## Status

Completed learning project retained as part of my Python, Linux, and QA portfolio.

## Security note

Credentials and private keys must not be committed to the repository.

## Safe, practical SSH path / Практическая программа

[Secure SSH automation lab](docs/secure-ssh-automation-lab.md) covers host-key verification, least privilege, safe read-only commands, Python/Paramiko, logging and **synthetic** QA.

SSH can support an authorized Linux reporting job or an isolated automation test. This does not mean the legacy `deploy.py` is a production deployment solution or has been executed recently.

**Legacy security boundary:** historical training scripts can contain hardcoded example connection values. Do not reuse them; a separate secrets and Git-history audit is needed before calling this repository fully sanitized.

**RU:** SSH полезен для автоматизации на Linux, но только в согласованной среде. Здесь — методология, тестовые сценарии и безопасность, без рабочих серверов или ключей.
