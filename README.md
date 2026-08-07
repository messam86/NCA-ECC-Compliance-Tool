

NCA_ECC_2_2024_Assessment_Tool(1).html
File
Can you add readme contents for this file

Yes. I’ll review the HTML tool first so the README accurately describes its purpose, features, scoring logic, and how to use it. I’m using the file-management skill because this README will accompany your existing assessment tool.

Reviewed assessment tool and library guidance
I can see this is more than a static checklist: it includes the full ECC assessment table, a compliance dashboard, gap analysis, and CSV export. I’m checking the exact status values and compliance calculation now so the README doesn’t overstate or misdescribe anything.

Inspected assessment tool HTML, dependencies, skill counts, README, and applied a patch
The README is drafted and matched to the actual code. I also included one important operational note: the current HTML keeps assessment entries only for the active browser session, so users should export the CSV before refreshing or closing the page.


Did you finish read me contents or not yet

Yes, Mohamed — it is completely finished. ✅

Download the completed README


NCA_ECC_2_2024_Assessment_Tool_README.md
Document


No file chosen
NCA_ECC_2_2024_Assessment_Tool_README.md


NCA ECC-2:2024 Assessment Tool
Overview
The NCA ECC-2:2024 Assessment Tool is a standalone, browser-based compliance assessment tool designed to support assessments against the Saudi National Cybersecurity Authority (NCA) Essential Cybersecurity Controls (ECC-2:2024).

The tool provides a simple interface for reviewing ECC controls, assigning a compliance status, monitoring overall compliance, identifying gaps, documenting remediation actions, and exporting the assessment results to CSV.

Key Features
108 assessment entries covering four ECC cybersecurity domains.

Status selection for every control: Compliant, Partially Compliant, Non-Compliant, or Not Applicable.

Interactive dashboard showing total controls, assessed controls, compliance status counts, and overall compliance rate.

Visual compliance-status chart.

Automatic gap analysis for Partially Compliant and Non-Compliant controls.

Remediation-action field for every identified gap.

CSV export containing control information, assessment status, and remediation actions.

Responsive interface suitable for desktop and mobile browsers.

Standalone HTML design with no installation or web server required.

ECC Domains Covered
Cybersecurity Governance

Cybersecurity Defense

Cybersecurity Resilience

Third-Party and Cloud Computing Cybersecurity

How to Use
Download NCA_ECC_2_2024_Assessment_Tool(1).html to your computer.

Open the HTML file using a modern browser such as Google Chrome or Microsoft Edge.

Click Start Assessment.

Open the Assessment page and review each ECC control.

Select the appropriate compliance status for every applicable control.

Open Dashboard to review assessment progress and the calculated compliance rate.

Open Gap Analysis to review Partially Compliant and Non-Compliant controls.

Enter the required remediation action for each identified gap.

Click Export CSV to download the assessment results for reporting or further analysis in Excel.

Compliance Status Definitions
Status	Meaning
Compliant	The control requirements are implemented and satisfied.
Partially Compliant	Some requirements are implemented, but gaps remain.
Non-Compliant	The control requirements are not adequately implemented.
Not Applicable	The control does not apply to the assessed scope or environment.
Compliance Rate
The dashboard calculates the compliance rate using:

Compliance Rate = Compliant / (Compliant + Partially Compliant + Non-Compliant) × 100

Controls marked Not Applicable are excluded from the compliance-rate denominator.

Gap Analysis
The Gap Analysis page automatically displays controls assessed as:

Partially Compliant

Non-Compliant

For each gap, the assessor can document a Remediation Action describing the corrective action required to achieve compliance.

CSV Export
The exported CSV includes:

Domain

Subdomain

Control ID

Control Description

Status

Remediation Action

The CSV is UTF-8 encoded for compatibility with Microsoft Excel.

Data Handling and Important Limitation
The tool runs locally in the browser and does not contain external network calls or server-side components. Assessment values are stored in memory only for the current page session. Refreshing or closing the HTML page will clear entered statuses and remediation actions unless they have already been exported to CSV.

For important assessments, export the CSV before closing or refreshing the browser.

Browser Compatibility
Recommended browsers:

Google Chrome

Microsoft Edge

Mozilla Firefox

If CSV download is blocked when opening the file locally, try Chrome or Edge and allow the browser to download the generated file.

Intended Use
This tool can support:

NCA ECC-2:2024 gap assessments

Internal compliance reviews

Cybersecurity audits and readiness assessments

Corrective-action and remediation tracking

Management compliance reporting

Disclaimer
This is an independent assessment aid and is not an official NCA product. It should be used together with the official NCA ECC-2:2024 publication, applicable NCA guidance, organizational scope, and professional judgment. Use of this tool does not by itself demonstrate or guarantee regulatory compliance.



NCA_ECC_2_2024_Assessment_Tool_README.md


NCA ECC-2:2024 Assessment Tool
Overview
The NCA ECC-2:2024 Assessment Tool is a standalone, browser-based compliance assessment tool designed to support assessments against the Saudi National Cybersecurity Authority (NCA) Essential Cybersecurity Controls (ECC-2:2024).

The tool provides a simple interface for reviewing ECC controls, assigning a compliance status, monitoring overall compliance, identifying gaps, documenting remediation actions, and exporting the assessment results to CSV.

Key Features
108 assessment entries covering four ECC cybersecurity domains.

Status selection for every control: Compliant, Partially Compliant, Non-Compliant, or Not Applicable.

Interactive dashboard showing total controls, assessed controls, compliance status counts, and overall compliance rate.

Visual compliance-status chart.

Automatic gap analysis for Partially Compliant and Non-Compliant controls.

Remediation-action field for every identified gap.

CSV export containing control information, assessment status, and remediation actions.

Responsive interface suitable for desktop and mobile browsers.

Standalone HTML design with no installation or web server required.

ECC Domains Covered
Cybersecurity Governance

Cybersecurity Defense

Cybersecurity Resilience

Third-Party and Cloud Computing Cybersecurity

How to Use
Download NCA_ECC_2_2024_Assessment_Tool(1).html to your computer.

Open the HTML file using a modern browser such as Google Chrome or Microsoft Edge.

Click Start Assessment.

Open the Assessment page and review each ECC control.

Select the appropriate compliance status for every applicable control.

Open Dashboard to review assessment progress and the calculated compliance rate.

Open Gap Analysis to review Partially Compliant and Non-Compliant controls.

Enter the required remediation action for each identified gap.

Click Export CSV to download the assessment results for reporting or further analysis in Excel.

Compliance Status Definitions
Status	Meaning
Compliant	The control requirements are implemented and satisfied.
Partially Compliant	Some requirements are implemented, but gaps remain.
Non-Compliant	The control requirements are not adequately implemented.
Not Applicable	The control does not apply to the assessed scope or environment.
Compliance Rate
The dashboard calculates the compliance rate using:

Compliance Rate = Compliant / (Compliant + Partially Compliant + Non-Compliant) × 100

Controls marked Not Applicable are excluded from the compliance-rate denominator.

Gap Analysis
The Gap Analysis page automatically displays controls assessed as:

Partially Compliant

Non-Compliant

For each gap, the assessor can document a Remediation Action describing the corrective action required to achieve compliance.

CSV Export
The exported CSV includes:

Domain

Subdomain

Control ID

Control Description

Status

Remediation Action

The CSV is UTF-8 encoded for compatibility with Microsoft Excel.

Data Handling and Important Limitation
The tool runs locally in the browser and does not contain external network calls or server-side components. Assessment values are stored in memory only for the current page session. Refreshing or closing the HTML page will clear entered statuses and remediation actions unless they have already been exported to CSV.

For important assessments, export the CSV before closing or refreshing the browser.

Browser Compatibility
Recommended browsers:

Google Chrome

Microsoft Edge

Mozilla Firefox

If CSV download is blocked when opening the file locally, try Chrome or Edge and allow the browser to download the generated file.

Intended Use
This tool can support:

NCA ECC-2:2024 gap assessments

Internal compliance reviews

Cybersecurity audits and readiness assessments

Corrective-action and remediation tracking

Management compliance reporting

Disclaimer
This is an independent assessment aid and is not an official NCA product. It should be used together with the official NCA ECC-2:2024 publication, applicable NCA guidance, organizational scope, and professional judgment. Use of this tool does not by itself demonstrate or guarantee regulatory compliance.



