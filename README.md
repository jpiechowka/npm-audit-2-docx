# npm-audit-2-docx

Parse npm audit reports and create docx document with summary of vulnerabilities

### Requirements
Pyhton-docx is required to run this script (https://python-docx.readthedocs.io/en/latest/). It can be installed by running ```pip install python-docx```

### Usage
1. Create npm audit report ```npm audit --parseable &> npm-audit-report.txt```
2. Move report file to ```npm``` directory alongside the script
3. Run ```python3 ./npm-audit-2-docx.py```
