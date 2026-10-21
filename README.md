# Linux Server Operations Lab

A small, self-maintained Linux server environment on AWS EC2 (Ubuntu), built to practise deploying, securing, monitoring, troubleshooting and recovering a service.

**Stack:** AWS (EC2, S3, IAM) · Ubuntu · C++ (CMake) · Nginx · PostgreSQL · systemd · Bash · Ansible · GitHub Actions · Git

## Roadmap

Work is split into phases. They aren't time-boxed; the status column is updated as each phase lands.

| Phase                           | Outcome                                                                               | Status      |
| ------------------------------- | ------------------------------------------------------------------------------------- | ----------- |
| 0. Foundations                  | AWS account, local tooling, repository conventions                                    | In progress |
| 1. CI foundation                | Automated checks on every push: ShellCheck, shfmt, gitleaks, yamllint                 | Planned     |
| 2. Server baseline              | Hardened Ubuntu EC2 instance: key-only SSH, firewall, automatic security updates      | Planned     |
| 3. Web service                  | C++ service behind Nginx with PostgreSQL and HTTPS, managed by systemd                | Planned     |
| 4. Automation                   | Tested Bash tooling for provisioning, health checks, backups and deployment           | Planned     |
| 5. Monitoring and alerting      | Scheduled checks with systemd timers, journald logging, alerts on failure             | Planned     |
| 6. Recovery and troubleshooting | Off-server backups, restore drills, documented failure scenarios and incident reports | Planned     |
| 7. Configuration as code        | Ansible playbooks that rebuild the whole environment                                  | Planned     |
| 8. Quality hardening            | Sanitizer builds, release automation, required checks before merge                    | Planned     |
| 9. Documentation                | Architecture diagram, runbook and recovery procedure                                  | Planned     |
| 10. Extensions                  | Optional deep dives, such as storage and LVM, Prometheus and Grafana, or Terraform    | Optional    |

## License

TBD
