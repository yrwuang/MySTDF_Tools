# MySTDF_Tools

MySTDF_Tools publishes the Windows portable releases for **MySTDF**, an integrated STDF conversion, project review, analysis, AI triage, and report-export tool.

Precompiled Windows portable packages are provided via **GitHub Releases**.

## Current Workflow

MySTDF is now a single portable application. Use the same app to convert raw STDF/archive inputs, open generated databases, review project folders, analyze fail patterns, and export reports.

```text
Raw STDF / archive files
(*.stdf, *.std, *.zip, *.gz, *.tar, *.7z, ...)
        |
        v
MySTDF portable app
- Convert STDF / Archive
- Project Manager batch staging
        |
        +--> MySTDF DB (*.db)
        +--> optional Excel workbook (*.xlsx)
        +--> optional Yield Overview / AI PPT (*.pptx)
        |
        v
Open DB / Project Manager review
        |
        v
Analysis and triage
- Wafer maps and probability plots
- Bin pareto and site checks
- Startup AI and TSR simulation
- Correlation and sanity checks
- Fail Signature / PinMap review
        |
        v
Export handoff reports
- Tables / simulation results to Excel
- Combo plots to PPT
- First Fail / Fail Summary to PPT
- Compare Summary to PPT
```

## Main Capabilities

- Convert STDF and common archive inputs into MySTDF SQLite databases.
- Open one or more existing MySTDF `.db` files for detailed review.
- Use Project Manager to stage many raw files, build per-file DB caches, and review catalog summaries.
- Generate wafer maps, probability plots, bin pareto views, site summaries, trellis views, radial profiles, and fail traces.
- Run Startup AI, TSR simulation, selected-row refresh, correlation checks, and sanity checks.
- Review O/S, Scan, IDDQ, and role-based signatures with Fail Signature Check.
- Configure PinMap / BallMap data and create Composite PinMap views.
- Export Excel and PowerPoint reports for engineering handoff.

## Download

Download the latest Windows portable package from the **GitHub Releases** page:

https://github.com/yrwuang/MySTDF_Tools/releases/latest

Each release normally includes:

- `MySTDF_<version>_Portable.zip`
- `MySTDF_<version>_Portable.zip.sha256.txt`
- `User_Guide.pdf`
- `version.json`

## Quick Start

1. Download the latest `MySTDF_<version>_Portable.zip` from Releases.
2. Extract the ZIP to a local folder.
3. Run `MySTDF.exe` from the extracted portable folder.
4. Choose `Convert STDF / Archive` for raw STDF inputs, or `Open DB` for existing MySTDF `.db` files.
5. Use `Project Manager` for folder-based, many-file review workflows.

## License & Usage Notice

- These tools are provided free of charge.
- Usage is **NON-COMMERCIAL ONLY**.
- Commercial use, resale, or redistribution for profit is not permitted without prior written permission from the author.
- License validity for released binaries is stated in the corresponding release notes and included documentation.

## Disclaimer

This software is provided "as is", without warranty of any kind, express or implied. The author shall not be liable for any damages arising from the use of this software.

## Author

Author: Yeeren Wuang  
Email: yrwuang@gmail.com  
Web: www.besteda.com
