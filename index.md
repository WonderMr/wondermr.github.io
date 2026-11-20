# Alexey Zhuchkov

Engineer in Barcelona, Spain. AI agent tooling, DevOps on AWS and Kubernetes, more than ten years in banking and fintech.

- **Email:** <a id="email" href="#" data-u="em" data-d="moc.rmrednow">enable JavaScript to see the address</a>
- **LinkedIn:** [linkedin.com/in/alexey-zhuchkov-1b499423](https://www.linkedin.com/in/alexey-zhuchkov-1b499423/)
- **GitHub:** [github.com/WonderMr](https://github.com/WonderMr)

<script>
  (function () {
    var link = document.getElementById("email");
    var reverse = function (s) { return s.split("").reverse().join(""); };
    var address = reverse(link.dataset.u) + "@" + reverse(link.dataset.d);
    link.href = "mailto:" + address;
    link.textContent = address;
  })();
</script>

## About

Engineer in IT since 2004, more than ten years of it in banking and fintech. Creator and maintainer of Agents-Core, an open-source MCP server that gives AI coding agents specialist roles, repeatable workflows and contract-checked delegation. Background in DevOps on AWS and Kubernetes, 1C:Enterprise architecture and high-load databases, and team leadership at Tinkoff Bank, working directly with business stakeholders on requirements.

## Open source

### Agents-Core: creator and maintainer, 01/2026 to present

[github.com/IEZhu/Agents](https://github.com/IEZhu/Agents) ▪ [agents-core.ai](https://agents-core.ai) ▪ Python, MIT licence

- Local MCP server for Claude Code, Codex, Cursor and other MCP clients: 46 specialist personas backed by 89 skills, 57 reasoning implants and 8 shared rules, routed through a local embedding model with no external API key.
- 20 Markdown workflows (pull request review, change premortem, issue planning and implementation, documentation refresh and others), per-repository memory and hash-pinned artifact manifests.
- Delegation as a contract: the parent prepares a bounded worker role with acceptance criteria and a result schema, and every returned result is validated against the stored contract before it is accepted. The check is structural and documented as such: [design note](https://github.com/IEZhu/Agents/blob/main/docs/subagent-contract.md).
- Solo project: 1,696 of 1,697 commits, 361 merged pull requests, 8 releases, 251 test files, CI for the runtime, instruction signing, documentation quality and vulnerability scanning (figures as of November 2026).

### Nikita: main author, 2023 to present

[github.com/IEZhu/Nikita](https://github.com/IEZhu/Nikita) ▪ Python, GPL-3.0

- Exports 1C:Enterprise event logs to ClickHouse, Solr and Redis, with an optional MCP endpoint for read-only ClickHouse queries.

### blincho

[blincho.app](https://blincho.app) ▪ [github.com/WonderMr/blincho](https://github.com/WonderMr/blincho) ▪ MIT licence

- Free screen break reminder for macOS, Windows and Linux.

### Earlier tools for 1C:Enterprise administrators

[bash1c](https://github.com/WonderMr/bash1c) (log analysis in Bash and Perl), [Loggie](https://github.com/WonderMr/Loggie) (data change logging), [C1Updater](https://github.com/WonderMr/C1Updater) (unattended updates in PowerShell).

## Experience

### Plata: DevOps Engineer, 10/2025 to present

- Run and develop cloud infrastructure on AWS and Kubernetes: infrastructure as code with Terraform, CI/CD with GitLab CI, monitoring with Prometheus and Grafana.

### Independent 1C:Enterprise developer and consultant, remote, 09/2022 to 09/2025

- Development and support of 1C:Enterprise systems for the fintech clients Vivid Money (Germany) and Plata (Mexico): configurations, integrations, PostgreSQL-based deployments on AWS, performance diagnostics.

### Tinkoff Bank: Team Lead, Moscow, 06/2019 to 09/2022

- Led the development and support team of the 1C-based accounting service for small and medium-sized business clients.
- Worked with business stakeholders as an analyst: gathered requirements, set development tasks, delivered integrations with internal systems and external services.
- Took part in the team's move of 1C development to Git with automated delivery and in consolidating 2,000 separate databases into 14; presented the case at Infostart Event 2021.
- Introduced proactive monitoring and BI on ClickHouse and Metabase; moved the service to PostgreSQL.
- Led the rollout of a password storage system for 300+ users and 20,000+ records.

### PIK Group: Architect, Moscow, 08/2018 to 06/2019

- Designed and administered the 1C infrastructure; led a development team of up to 10: tasks and requirements, code review, feedback and mentoring.
- Built monitoring of user sessions and licences, proactive problem alerts and automated configuration updates; final tier of support for complex incidents.

### CloudDC: Senior 1C Specialist, Moscow, 11/2016 to early 2018

- Designed and ran high-load fault-tolerant 1C clusters; led a team of up to 4.
- Proactive monitoring and performance tuning; final escalation point for complex incidents.

### Magnit: Senior Specialist, 1C services, Krasnodar, 07/2011 to 10/2016

- Designed and administered a group of 1C clusters; analysed and tuned high-load databases; automated business processes.
- Grew from technical support specialist to lead specialist.

### Raiffeisen Bank Russia: Specialist, Krasnodar, 02/2009 to 07/2011

- A year of phone support for clients, plus development work within the support team.
- Ran a server group (Oracle, Active Directory, backup); automated banking processes in C, PL/SQL, VBScript and JavaScript; supported payment exchange documentation with the Central Bank.

### Sberbank: SQL Administrator, Pyatigorsk, 08/2004 to 08/2006

- Supported the regional card payment system (AIS Sbercard), payroll projects and a regional group of ATMs.

## Talks and publications

- "Our path to Git: the story of one CI/CD implementation" (in Russian), Infostart Event 2021, Moscow: [article and video](https://infostart.ru/1c/articles/1947598/).
- Articles and tools for 1C:Enterprise administrators on Infostart, 2013 to 2023: [author profile](https://infostart.ru/profile/232316/public/).

## Skills

- **AI engineering:** MCP servers, agent personas and skills, workflows, subagent delegation with result contracts, repository memory; Claude Code, Codex, Cursor.
- **Languages:** Python, SQL, Bash, PowerShell, 1C:Enterprise (BSL); earlier C and PL/SQL.
- **Platform:** AWS, Kubernetes, Docker, Helm, Terraform, GitLab CI, Jenkins, Prometheus, Grafana, Linux.
- **Data:** PostgreSQL, ClickHouse, Oracle, MS SQL, Redis, Metabase.

## Education

Saint Petersburg State University of Engineering and Economics, 1999 to 2004. Information Systems in Economics; qualification: Economist.

## Languages

Russian (native) ▪ English (professional working proficiency)
