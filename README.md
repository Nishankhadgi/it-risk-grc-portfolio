# IT Risk & GRC Portfolio

A portfolio of two **self-directed learning simulations** demonstrating foundational skills in IT General Controls (ITGC), IT Application Controls (ITAC), control testing, risk registers, remediation tracking, third-party risk assessment, Excel, and Power BI.

> **Important:** All organizations, vendors, records, dates, outcomes, findings, risk scores, owners, and policy criteria in this repository are fictional and synthetic. These projects are not client engagements, actual audits, assurance opinions, or evidence of work performed for an employer.

## Projects at a glance

| Project | Purpose | Tools | Contents |
|---|---|---|---|
| [ITGC Control Testing & Remediation](ITGC-Control-Testing/) | Practice control design, evidence review, sample-level test outcomes, findings, risk linkage, and remediation monitoring | Excel, Power BI, DAX, CSV | Excel workpaper, synthetic data, Power BI project, dashboard preview, instructions |
| [Third-Party Vendor Risk Assessment](Third-Party-Vendor-Risk/) | Practice vendor inventory review, assurance-evidence evaluation, weighted risk scoring, findings, and recommended actions | Excel, CSV, Power BI concepts, DAX | Vendor workbook, six fictional vendor records, assessment rubric, findings, dashboard preview, instructions |

## Project 1 — ITGC Control Testing & Remediation

![ITGC dashboard preview](ITGC-Control-Testing/screenshots/dashboard_preview.png)

The simulated testing pack contains **20 sample-level test records across 10 illustrative controls**: 12 Pass, 6 Fail, and 2 Needs Follow-up. The associated risk register and remediation tracker link eight synthetic findings to risks, action owners, target dates, and closure evidence expectations.

**Explore:**
- [Excel workbook and source data](ITGC-Control-Testing/Excel/)
- [Power BI project folder](ITGC-Control-Testing/PowerBI/ITGC_Control_Testing_Report/)
- [Instructions for opening the Power BI project](ITGC-Control-Testing/PowerBI/ITGC_Control_Testing_Report/README_OPEN_IN_POWER_BI.md)
- [Project guide](ITGC-Control-Testing/Excel/README_Project_Guide.md)

## Project 2 — Third-Party Vendor Risk Assessment

![Vendor risk dashboard preview](Third-Party-Vendor-Risk/screenshots/dashboard_preview.png)

The practice dataset covers **six fictional SaaS/service vendors** and six synthetic findings. It evaluates areas such as service criticality, data classification, independent assurance, access controls, data protection, incident notification, subprocessors, and complementary user-entity controls.

The weighted scoring formula is a **custom practice rubric**, not a mandatory industry standard. The project is intended to demonstrate structured assessment and documentation, not to certify a vendor as secure.

**Explore:**
- [Excel workbook and source data](Third-Party-Vendor-Risk/Excel/)
- [Project guide](Third-Party-Vendor-Risk/Excel/README_Vendor_Risk_Guide.md)

## Skills demonstrated

- ITGC / ITAC fundamentals and sample-based control testing
- Evidence review, exception documentation, and follow-up questions
- Risk register design, likelihood/impact scoring, and risk prioritization
- Remediation tracking, ownership, target dates, and closure evidence
- Third-party security questionnaires and assurance-report review concepts
- Excel-based analysis, Power BI report design concepts, and DAX measures
- Clear documentation of assumptions, limitations, and recommended actions

## How to use this repository

1. Start with the `README_Project_Guide.md` or `README_Vendor_Risk_Guide.md` in each project's `Excel` folder.
2. Open the Excel workbook and inspect the data dictionary, test criteria, findings, and scoring assumptions.
3. For the ITGC Power BI project, install Power BI Desktop, extract/clone this repository, and open `ITGC-Control-Testing/PowerBI/ITGC_Control_Testing_Report/ITGC_Control_Testing_Report.pbip`.
4. Review the visuals, confirm the results against the workbook, and document your own observations. Power BI Desktop validation is required before treating the PBIP as a working report on your machine.
5. Be prepared to explain the data model, test criteria, risk formula, and limitations in an interview.

GitHub displays the report definitions, files, and screenshots; it does not render an interactive Power BI report directly in the repository page. The PBIP project is included as a source-controlled report project. A native `.pbix` file is not included.

## Methodological notes and limitations

- A missing item in a synthetic evidence pack is an evidence gap; it is not automatically proof that a control failed.
- A sample-level pass rate is not a population-wide conclusion about control effectiveness.
- The sample policy SLAs, due dates, risk scales, weights, rating thresholds, and outcomes are illustrative exercise assumptions.
- The NIST Cybersecurity Framework is used only as a conceptual framework lens; this repository does not claim an official control mapping or certification.
- No confidential, employer, customer, or real vendor information should be added to this public portfolio.

## References

- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [NIST CSF 2.0 publication](https://csrc.nist.gov/pubs/cswp/29/the-nist-cybersecurity-framework-csf-20/final)
- [Microsoft Learn: Get started with Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-getting-started)
- [Microsoft Learn: Power BI Desktop projects (PBIP)](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-overview)
- [GitHub Docs: About large files](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github)
