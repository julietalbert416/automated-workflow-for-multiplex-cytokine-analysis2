# automated-workflow-for-multiplex-cytokine-analysis

Automated workflow for multiplex cytokine analysis — Excel + VBA

Overview
This repository contains the macro-enabled Excel workbook and exported VBA source used to automate multiplex cytokine data processing and analysis.

Contents
- workbook/ : the Excel macro-enabled workbook (.xlsm)
- vba/ : exported VBA modules (.bas/.cls/.txt) — these make the code readable and versionable
- README.md : this file
- LICENSE : MIT license

Quick start
1. Clone the repository:
   git clone https://github.com/julietalbert416/automated-workflow-for-multiplex-cytokine-analysis.git
2. Open the workbook:
   - Open the .xlsm file in Excel (enable macros only if you trust the file).
3. View or edit the VBA:
   - In Excel press Alt+F11 to open the VBA editor, or open the exported .bas/.cls files in a text editor.

Recommended structure
- workbook/YourWorkbookName.xlsm
- vba/Module1.bas
- vba/Module2.bas
- vba/ThisWorkbook_code.txt

Security note
Make sure the workbook and modules do not contain any sensitive data (patient identifiers, passwords, API keys). Remove or anonymize any private data before uploading to a public repository.

License
This project is released under the MIT License — see LICENSE for details.