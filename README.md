# API Security Risk Analysis: ReqRes Products Endpoint

### Repository Overview
This repository contains the documentation and findings for a security risk analysis conducted against the ReqRes REST API. The assessment focuses specifically on the Products collection endpoint and follows the OWASP API Security Top 10 framework to identify and categorize potential vulnerabilities.

### Tools Used
* **Insomnia REST Client:** Utilized as the primary HTTP request tool for crafting, sending, and inspecting API calls [cite: 72, 81].
* **ReqRes (reqres.in):** A hosted REST API platform used as the live target for all security testing activities [cite: 14, 73].
* **OWASP API Security Top 10:** Employed as the core methodology for vulnerability classification and testing structure [cite: 5, 20, 74].

### Scope
* **Endpoint Focus:** The testing was strictly limited to the `/api/collections/products/records` endpoint and its associated authentication mechanisms [cite: 15, 76].
* **Testing Environment:** All activities were performed against a personal ReqRes project using legitimately obtained API keys [cite: 77].
* **Ethical Constraints:** No attempts were made to access data belonging to other users or to interfere with the ReqRes infrastructure [cite: 78].

### Methodology
* **Black-Box Testing:** The assessment followed a black-box approach, simulating an external attacker with valid credentials but no internal system knowledge [cite: 80].
* **Manual Analysis:** Requests were manually constructed within Insomnia to test for BOLA, excessive data exposure, and security misconfigurations [cite: 21-26, 81].
* **Risk Assessment:** Each finding was evaluated based on its exploitability and potential business impact, then classified by severity [cite: 82].

### File Structure
* **`API_Security_Risk_Analysis_Report.docx`**: The full detailed report containing the executive summary, findings matrix, and remediation steps.
* **`README.md`**: This file, providing high-level repository information and project context.
