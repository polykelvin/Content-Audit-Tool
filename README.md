# Content Audit Tool

The Content Audit Tool is a specialized, browser-based utility designed for high-performance keyword scanning and content compliance. This tool enables users to audit large volumes of text against extensive databases of restricted terms using optimized algorithms, ensuring security and internal standards are maintained.
<img width="1198" height="864" alt="image (3)" src="https://github.com/user-attachments/assets/99c0c4a9-b9fe-4795-86b0-14e72e667dad" />

---

## Core Capabilities

* **Multi-Engine Architecture:** Supports various scanning methodologies, ranging from high-efficiency pattern matching to typo-tolerant analysis.
* **Anti-Evasion Logic:** Identifies restricted content attempting to bypass filters through the use of special characters, symbols, or irregular spacing.
* **Client-Side Processing:** All scanning operations are performed locally within the browser. This ensures that sensitive data is never transmitted to external servers.
* **Rule Management:** Includes a built-in keyword library preview with real-time filtering for efficient database verification.
* **Exception Handling:** Supports whitelisting to prevent false positives for approved technical terms or official nomenclature.

---

## Scanning Methodologies

| Engine | Primary Use Case | Technical Description |
| :--- | :--- | :--- |
| **Aho-Corasick** | High-Volume Efficiency | Utilizes a finite-state machine to scan text in a single pass, regardless of dictionary size. |
| **Anti-Evasion** | Security Compliance | Employs smart regex mapping to detect "masked" words or character substitutions. |
| **Fuzzy Search** | Typo Identification | Powered by Fuse.js to identify approximate matches based on string proximity. |
| **Regex / Plain** | Exact Matching | Standard literal or pattern-based matching for strict compliance requirements. |

---

## Operational Guide

1. **Initialize Database:** Upload a CSV file containing a column labeled "Keyword."
2. **Verify Rules:** Utilize the Quick Filter within the rule preview to confirm the presence of specific parameters.
3. **Configure Whitelist:** Input approved terms into the whitelist field to exclude them from the audit results.
4. **Input Data:** Provide the text or Markdown content intended for review.
5. **Execute Audit:** Select "Run Security Audit" to generate an immediate report highlighting violations and total match counts.

---

## Privacy and Data Security

Data integrity and privacy are fundamental to this application. All input text and uploaded databases are processed exclusively within the local browser environment. No data is stored externally or transmitted over the network during the audit process, making it suitable for secure corporate or academic environments.

---
