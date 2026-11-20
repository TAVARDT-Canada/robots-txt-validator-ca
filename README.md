# Robots.txt Validator | TAVARDT Canada

[![Robots.txt Validator](https://img.shields.io/badge/TAVARDT-Robots.txt-5b3cf5.svg)](https://tools.tavardt.com/ca/robots-txt-validator/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-Canada-00C853.svg)](https://ag.tavardt.com/ca/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Automated robots.txt audit tool for Canadian digital properties, ensuring intended search bot crawling without compromising secure paths.

Developed and maintained by the digital architecture and crawl engineering team at **[TAVARDT Canada](https://ag.tavardt.com/ca/)**.

---

## Robots.txt Audit Capabilities

* **De-indexing Prevention**: Automated checks for accidental disallow rules compromising Canadian digital properties.
* **Bot Segmentation**: Establishes clear boundaries for search engine discovery and autonomous AI agents.
* **Sitemap Integration**: Ensures proper linkage and discovery of XML sitemaps by web crawlers.
* **Syntax and Path Safety**: Validates path matching, exclusion patterns, and private directory protection.
* **Crawl Posture Rating**: Objective 0 to 100 evaluation with actionable technical optimization steps.

---

## Installation and Execution

Requires Python 3.8 or higher using standard library modules.

```bash
git clone https://github.com/TAVARDT-Canada/robots-txt-validator-ca.git
cd robots-txt-validator-ca
python robots_validator.py https://example.ca
```

To output structured JSON:

```bash
python robots_validator.py https://example.ca --json
```

---

## Online Diagnostic Platform

For interactive robots.txt validation and crawler rule testing:

* **[Official Robots.txt Validator](https://tools.tavardt.com/ca/robots-txt-validator/)**
* **[TAVARDT Canada Portal](https://ag.tavardt.com/ca/)**

---

## Canadian Digital Standards and Crawl Advisory

For web crawler governance and technical alignment with Robots Exclusion Protocol and Canadian Web Standards, connect with the engineering group at **[TAVARDT Canada](https://ag.tavardt.com/ca/contact/)**.
