<div align="center">
<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a><a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</div>
<div align="center">
  <img src="assets/banner.svg" alt="Awesome API Discovery Platform Banner" width="100%" />
</div>
# 🚀 Awesome API Discovery Platform
> A curated list of awesome API discovery platforms, tools, and resources for comprehensive API security and observability.

## 🔍 Similar Projects to API Discovery Platforms

**API Discovery Platforms** automatically find, inventory, catalog, and often secure APIs across an organization’s environment. They detect shadow, zombie, and rogue APIs by analyzing traffic, code, gateways, and runtime behavior, then help teams maintain an accurate API inventory and apply security controls. Leading commercial platforms include 42Crunch, Noname Security, Traceable AI, Salt Security, Postman API Network, SmartBear SwaggerHub, Akita, FireTail, Cloudflare API Discovery, and Cequence.

Below is a **curated list** of notable platforms and their open-source equivalents. Fully featured commercial-grade API discovery and runtime security platforms remain predominantly proprietary. Open-source strength lies in API scanning, specification analysis, traffic inspection, and code-based endpoint discovery tools that teams can combine into a custom discovery workflow.

## 🏢 🌐 SaaS / Hosted Platforms

| Platform | Description | Pricing | Free Tier Limit | Company Valuation |
| :--- | :--- | :--- | :--- | :--- |
| **[Cloudflare API Discovery](https://www.cloudflare.com/)** | Specialized API discovery, security, and observability solutions. | Enterprise Plan Only | No Free Tier | ~ Billion |
| **[Postman API Network](https://www.postman.com/)** | Popular platform for API design, documentation, discovery, and collaboration. | Free / Paid plans | Free Tier: Single user only (No Private network) | ~.6 Billion |
| **[SmartBear SwaggerHub](https://swagger.io/tools/swaggerhub/)** | Popular platform for API design, documentation, discovery, and collaboration. | Free / Paid plans | Free Tier: Basic features, limited projects | ~.0 Billion |
| **[Salt Security](https://salt.security/)** | API security platform focused on discovery, threat detection, and protection using behavioral analysis. | Custom Quotes | No Free Tier (Free assessment available) | ~.4 Billion |
| **[Cequence](https://www.cequence.ai/)** | Specialized API discovery, security, and observability solutions. | Custom Quotes | No Free Tier (Free assessments available) | ~ Million |
| **[Noname Security](https://nonamesecurity.com/)** (Akamai) | Comprehensive API security platform with strong discovery, inventory, and runtime protection. | Custom Quotes | No Free Tier | ~ Million |
| **[Traceable AI](https://www.traceable.ai/)** | API security and observability platform with discovery and threat detection capabilities. | Free / Paid plans | Free Tier available ($0/endpoint/month) | ~ Million |
| **[42Crunch](https://42crunch.com/)** | API security platform emphasizing contract security, OpenAPI analysis, and shift-left protection. | Freemium / Paid plans | Free Tier: 100 audits & scans / month | ~ Million |
| **[FireTail](https://www.firetail.io/)** | Specialized API discovery, security, and observability solutions. | Free / Paid plans | Free Tier: Up to 5 APIs, 1M logs/month | ~ Million |
| **[Akita Software](https://www.akitasoftware.com/)** | Specialized API discovery, security, and observability solutions. | N/A (Acquired by Postman) | N/A | Acquired |

## 🔓 🛠️ Open-Source Software

### 🛡️ API Scanning, Testing & Discovery Tools
- **[Nuclei](https://github.com/projectdiscovery/nuclei)** [![Stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social&color=white)](https://github.com/projectdiscovery/nuclei/stargazers) — Fast, template-based vulnerability scanner from ProjectDiscovery. Includes extensive community templates for API security issues (BOLA/IDOR, GraphQL, JWT problems, exposed endpoints, etc.) and is widely used for discovery and continuous scanning.
- **[OWASP ZAP](https://www.zaproxy.org/)** [![Stars](https://img.shields.io/github/stars/zaproxy/zaproxy?style=social&color=white)](https://github.com/zaproxy/zaproxy/stargazers) — The leading open-source DAST tool with strong API support. Imports OpenAPI/Swagger specifications, actively scans REST and GraphQL APIs for vulnerabilities (including OWASP API Top 10 issues), and can be used for discovery and security testing in CI/CD.
- **[Dredd](https://github.com/apiaryio/dredd)** [![Stars](https://img.shields.io/github/stars/apiaryio/dredd?style=social&color=white)](https://github.com/apiaryio/dredd/stargazers) — API testing framework for validating API description formats against backend implementations.
- **[Kiterunner](https://github.com/assetnote/kiterunner)** [![Stars](https://img.shields.io/github/stars/assetnote/kiterunner?style=social&color=white)](https://github.com/assetnote/kiterunner/stargazers) — Excellent API discovery and fuzzing tool tailored specifically for content discovery and endpoint enumeration.
- **[RESTler](https://github.com/microsoft/restler-fuzzer)** [![Stars](https://img.shields.io/github/stars/microsoft/restler-fuzzer?style=social&color=white)](https://github.com/microsoft/restler-fuzzer/stargazers) — The first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs.
- **[APIKit](https://github.com/API-Security/APIKit)** [![Stars](https://img.shields.io/github/stars/API-Security/APIKit?style=social&color=white)](https://github.com/API-Security/APIKit/stargazers) — Open-source Burp Suite extension focused on API discovery. Detects and parses API documentation (Swagger/OpenAPI, GraphQL, Spring Actuator, WSDL, etc.) from traffic and turns it into testable requests.
- **[APIClarity](https://github.com/openclarity/apiclarity)** [![Stars](https://img.shields.io/github/stars/openclarity/apiclarity?style=social&color=white)](https://github.com/openclarity/apiclarity/stargazers) — Open source cloud native visibility tool for APIs, focused on discovering shadow and zombie APIs by analyzing traffic.

### 📜 Specification, Catalog & Code-Based Discovery
- **OpenAPI / Swagger tooling ecosystem** — Tools such as Swagger Editor, OpenAPI Generator, and Spectral (for linting) help teams document and discover APIs from specifications.
- Code-based API endpoint discovery projects (Python/JavaScript scanners that parse source code or frameworks to generate OpenAPI specs and inventory endpoints).
- **APIs.io** and related open API directory projects that catalog public APIs using the APIs.json specification.

### 🚦 Traffic Inspection & Supporting Tools
- **mitmproxy** — Powerful open-source interactive HTTPS proxy for manual and scripted API traffic inspection, replay, and analysis.
- Network and runtime visibility tools built on eBPF or proxy logs that teams combine with the scanners above for broader discovery.
- General security scanners (Trivy, Semgrep, etc.) that can surface API-related misconfigurations and secrets as part of a broader inventory process.

### 💡 Typical Open-Source Approach
1. **Specification & code discovery** — Parse OpenAPI/Swagger files and source code to build an initial inventory.
2. **Traffic-based discovery** — Use proxies, gateway logs, or eBPF sensors to find shadow APIs.
3. **Security testing** — Run OWASP ZAP + Nuclei against the discovered inventory.
4. **Catalog & governance** — Store results in an internal developer portal, Backstage, or a simple database + dashboard.
5. **Continuous monitoring** — Integrate the above tools into CI/CD and runtime observability pipelines.

While this stack does not yet match the automated, ML-driven discovery and runtime protection of Salt, Noname, or Traceable, it provides a transparent, self-hosted foundation for API inventory and security that many organizations successfully use.

---

🤝 **How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to API discovery, API inventory, API security testing, or OpenAPI tooling.

📄 **License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open API tools help teams gain visibility and control over their API attack surface! 🔍
##  Star History
<div align="center">
<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Api-Discovery-Platform&type=date&legend=bottom-right">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Api-Discovery-Platform&type=date&theme=dark&legend=bottom-right" />
<source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Api-Discovery-Platform&type=date&legend=bottom-right" />
<img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Api-Discovery-Platform&type=date&legend=bottom-right" />
</picture>
</a>
</div>
