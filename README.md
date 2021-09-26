# Prerequisites 
* Define security requirements
* Define data classifications
* Define risk appetite 
* Define critial business processeses 
* Define development stack, instruments and frameworks
* Define security metrics (how to understand is a team good in security or not)


# Development lifecycle activities
| Stage | Activity | Target | Type | Automated | Scheduled |
| --- | --- | --- | --- | --- | --- |
| Demand on developement | Security Requirements Complaence | Analysts | Checklist | Partially | Every new business demand |
| Demand on developement | Scoring & Prioritization | Business owners | Tasks | No | Every sprint |
| Development | Security Code Review | Developers | Merge-request Approve | Partially | Every MR |
| Development | Security Autotests | Developers | Auto-tests | Yes | Every build |
| Build | Static Application Security Testing | Developers | Report | Yes | Every build |
| Build | Dynamic Application Security Testing | Developers | Report | Yes | Every build |
| Build | Dependency check | Developers | Report | Yes | Every build |
| Testing | Interactive Application Security Testing | Developers | Report | Yes | Every build |
| Testing | Internal Penetration Testing | Developers | Report | No | Every minor release |
| Testing | External Penetration Testing | Developers | Report | No | Every major release |
| Testing | Log Review | Developers | Report | Yes | Every Build |
| Deployment | Secure Deployment | Operations | Logs | Yes | Every Deploy |
| Deployment | Web Application Firewall | Operations | WAF rules | Partially | Every Deploy |

# Activities outside developement lifecycle
| Stage | Activity | Target | Type | Automated | Scheduled |
| --- | --- | --- | --- | --- | --- |
| Demand | Security Initiatives | Business owners | Tasks | No | On demand |
| Design | Detailed Security Requirements | Analysts, Architectures | Comments | No | On demand |
| Design | Secure Architecture | Analysts, Architectures | Comments | No | On demand |
| Design | Threat Modelling | Analysts, Architectures, Developers | Theat model | Partially | On demand |
| Deployment | Vulnerability Scanning | Operations | Report | Yes | Weekly |
| Deployment | Security Solutions Integration | Operations, Developers | Logs | Yes | Weekly |
| Maintenance | Pathing | Operations | Updates | Yes | Monthly |

# Non developlent activities
| Stage | Activity | Target | Type | Automated | Scheduled |
| --- | --- | --- | --- | --- | --- |
| Oranigational work | Trainings & Workshops | Developers, Operations, Analysts, QA | Worskshop, online school | No | Quaterly |
| Oranigational work | Awareness | Developers, Operations, Analysts, QA, Business owners, Executives | Newsletter | Partially | Weekly |
| Oranigational work | Security KPI | Business owners, Executives | Agreement | No | Yearly |
| Maintenance | Threat Hunting | Analysis, Developers | Logs | No | Quaterly |
| Maintenance | Bug Bounty | Analysis, Developers | Report | No | Continuously |

# Internal AppSec Activities
| Stage | Activity | Target | Type | Automated | Scheduled |
| --- | --- | --- | --- | --- | --- |
| Oranigational work | Security State Board | CISO, Business Owners | Report | Yes | Weekly |
| Design | Security TechRadar | CISO, Developers, Architectures | List of approved technoligies | No | Quaterly |
| Development | Security Coding Standards and Practices | Developers | Articles | No | Quaterly |
| Deployment | Secure Configuration Baselines | Operations | Baselines | No | Quaterly |
| Maintenance | Security Incident Management Process | RedTeam, BlueTeam | Process | No | Yearly |
| Maintenance | Restospective Analysis & Review | Application | Report | No | Quaterly |
