# LinkedIn Content Curator

Public overview of a governed, human-in-the-loop LinkedIn content workflow built on Microsoft Power Platform (Copilot Studio, Power Automate, Power Apps, SharePoint, Teams, Power BI).

Live page: https://scaruana33-code.github.io/linkedin-content-curator/

The apps and flows run inside a private Microsoft 365 tenant and are not hosted here. This repository holds only the static showcase page, sample-data previews, the public end user guide, and a no-login demo.

## Demo (no sign-in)

`demo/index.html` is a browser-only replica of the Start a Run and Content Approvals apps: start a run, pick an article at Gate 1, approve or edit the post at Gate 2, then see a mock LinkedIn post, run history, and metrics. It uses fictional sample articles (links go to example.com), stores state only in the visitor's browser (localStorage key `curator_demo_v1`), and makes no calls to Microsoft 365, email, Teams, or LinkedIn.

Live demo: https://scaruana33-code.github.io/linkedin-content-curator/demo/
