# npm-audit-2-docx

Parse npm audit reports and create docx document with summary of vulnerabilities

### Usage
1. Create npm audit report ```npm audit --parseable &> npm-audit-report.txt```
2. Move report file to ```npm``` directory
3. Run ```python3 ./npm-audit-2-docx.py```
