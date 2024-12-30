# Source

## **1. Open Vulnerability Databases**
These databases contain real-world vulnerabilities with detailed explanations.

### **Sources**:
- **[CVE Details](https://www.cvedetails.com/)**:
  - Provides extensive information about vulnerabilities categorized by language, software, and type.
  - Includes descriptions, severity, and links to patches.
- **[National Vulnerability Database (NVD)](https://nvd.nist.gov/)**:
  - Offers structured data feeds with CVSS scores for common vulnerabilities.
  - Downloadable JSON feeds for programmatic access.
- **[Exploit Database](https://www.exploit-db.com/)**:
  - A database of exploits, many with code samples for training.

---

## **2. Vulnerable Code Repositories**
Repositories hosting intentionally vulnerable code are excellent for creating labeled datasets.

### **Sources**:
- **[OWASP Vulnerable Web Applications Directory](https://owasp.org/www-project-vulnerable-web-applications-directory/)**:
  - Lists intentionally vulnerable applications like DVWA (PHP) and Juice Shop (JavaScript).
- **[VulnHub](https://www.vulnhub.com/)**:
  - Virtual machines with vulnerable applications for hands-on exploration.
- **[GitHub: Awesome Vulnerable Applications](https://github.com/infoslack/awesome-vulnerable-apps)**:
  - A curated list of intentionally insecure applications across various languages.

---

## **3. Static Code Analysis Tools**
These tools can generate labeled data by identifying vulnerabilities in large codebases.

### **Sources**:
- **[Bandit](https://github.com/PyCQA/bandit)** (Python): 
  - Detects security issues in Python code.
- **[Semgrep](https://semgrep.dev/)**:
  - Lightweight static analysis for multiple languages.
- **[CodeQL](https://codeql.github.com/)**:
  - A query-based analysis engine used by GitHub to detect vulnerabilities.

---

## **4. Educational Datasets**
Pre-curated datasets focused on teaching and studying secure coding.

### **Sources**:
- **[OWASP Security Knowledge Framework](https://owasp.org/www-project-security-knowledge-framework/)**:
  - Offers categorized coding examples with security insights.
- **[SATE IV Dataset](https://samate.nist.gov/SATE4.html)**:
  - A collection of secure and insecure code for testing static analysis tools.
- **[SAMATE Reference Dataset](https://samate.nist.gov/SRD/)**:
  - Provides test cases designed to evaluate static and dynamic analysis tools.

---

## **5. Real-World Codebases**
Large open-source projects often have associated bug reports and vulnerabilities that can be mined for data.

### **Sources**:
- **GitHub and GitLab**:
  - Search for repositories with known vulnerabilities using tags like `#vulnerability`, `#security`, or specific CVEs.
- **Apache Software Foundation Projects**:
  - Many Apache projects have a history of reported vulnerabilities with detailed fixes.
- **Historical Bug Reports**:
  - Use project issue trackers (e.g., JIRA, GitHub Issues) to collect details about vulnerabilities.

---

## **6. Research Papers and Benchmarks**
Research on vulnerability detection often comes with datasets.

### **Sources**:
- **[DARPA Cyber Grand Challenge](https://www.darpa.mil/program/cyber-grand-challenge)**:
  - Datasets used in DARPA’s cybersecurity competitions.
- **[Google Code Jam Solutions](https://codingcompetitions.withgoogle.com/codejam)**:
  - Provides real-world code samples to analyze security best practices.
- **Academic Datasets**:
  - Research papers from platforms like arXiv or Springer often provide code snippets in appendices.

---

## **7. Community Platforms**
Crowdsourced data from developer communities.

### **Sources**:
- **Stack Overflow**:
  - Questions and answers related to security vulnerabilities can be scraped (e.g., tagged `#security`, `#sql-injection`).
- **GitHub Discussions**:
  - Discussions on security issues in repositories can provide real-world context.

---

## **8. Vulnerability Challenges and CTF Platforms**
Platforms where users solve challenges related to specific vulnerabilities.

### **Sources**:
- **[picoCTF](https://picoctf.org/)**:
  - Challenges focused on common vulnerabilities.
- **[Hack The Box](https://www.hackthebox.com/)**:
  - Offers vulnerable machines for various programming environments.
- **[Root-Me](https://www.root-me.org/)**:
  - Challenges focused on insecure code exploitation.

---

## **9. Pre-Labeled Datasets**
Ready-to-use datasets for machine learning.

### **Sources**:
- **[BigCode Project](https://www.bigcode-project.org/)**:
  - Large datasets for machine learning in code analysis.
- **[OpenAI Codex](https://openai.com/research/codex)**:
  - Pretrained on secure and insecure code; examples can be extracted through its API.
- **[Google OSS-Fuzz](https://github.com/google/oss-fuzz)**:
  - Repository of fuzzing test cases for various languages and projects.

---

### **How to Use These Sources**

1. **Curate Data**: Collect code snippets with labeled vulnerabilities.
2. **Annotate**: Add security annotations (e.g., insecure/secure, vulnerability type).
3. **Augment**: Generate synthetic examples (e.g., modify secure code to introduce vulnerabilities).
4. **Preprocess**: Tokenize and structure the data for your model.
