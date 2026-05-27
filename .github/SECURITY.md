# Security Policy for PoseStudio.org

The PoseStudio team takes the security of our project and infrastructure seriously. 

Please note that this repository (`PoseStudio/posestudio.github.io`) is dedicated solely to the front-end website, documentation, and web infrastructure for PoseStudio.org. 

**If you have found a security vulnerability in the PoseStudio 3D software application itself, please refer to the security policy in the [main application repository](https://github.com/PoseStudio/PoseStudio).**

## Supported Versions

For the website and its associated build scripts, we only provide security updates for the current deployment.

| Version | Supported          |
| ------- | ------------------ |
| `main` branch (Live Site) | :white_check_mark: |
| Older branches / forks | :x:                |

## Reporting a Vulnerability

If you discover a security vulnerability regarding the posestudio.org website, its GitHub Pages configuration, or our front-end traffic routing/WAF implementation, please do not report it by opening a public GitHub issue.

Instead, please report it privately to the project maintainers.

**How to report:**
1. Email your findings to **Community Support community@posestudio.org**.
2. Include a clear description of the vulnerability, the steps required to reproduce it, and any potential impact.
3. If applicable, include information regarding the specific browser or user agent used during your testing.

**What to expect:**
* We will acknowledge receipt of your vulnerability report within 48 hours.
* We will send you regular updates about our progress in addressing the issue.
* Once the vulnerability is resolved and deployed, we will notify you and, with your permission, acknowledge your contribution to the community.

## Scope

We are particularly interested in reports regarding:
* Cross-Site Scripting (XSS) in our site architecture or documentation search tools.
* Misconfigurations in our domain routing or traffic mitigation rules.
* Compromised dependencies within our site build process.

We ask that you do not perform volumetric DDoS attacks or automated scanning that degrades the performance of the site for the community while researching vulnerabilities.
