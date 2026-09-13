# Excel2PPT 2.0 — release candidate 1

First public test installer for the Excel2PPT Windows add-in. This is a prerelease, ahead of the paid-plan launch.

- Excel ribbon and a single workbook setup table with source dropdowns.
- Compact, branded settings with separate Presentation and Source dropdowns tabs.
- Demo worksheet with sample data and a short tutorial.
- Dimension Finder with two-decimal placement values.
- Export preflight with actionable messages and prominent review warnings.
- Free mode and the Pro/Team activation interface.
- Compiled C# add-in running on Excel-DNA and .NET Framework 4.8.

Free mode exports one picture to a new presentation. Paid-plan activation remains pending the billing setup and live activation test.

## Verification and current limits

94 automated logic checks passed in both 32-bit and 64-bit .NET Framework test processes. Package checks and isolated installer checks passed. Dialog layouts were checked with enlarged fonts and small work areas without controlling a user's desktop.

These checks do not replace a live Excel-to-PowerPoint export test, a clean-machine installation test or a real purchase/activation/refund test. Those release checks remain outstanding. The installer is unsigned.

Download **Excel2PPT-2.0-Setup.exe**, save your work, and close Excel before installing. Re-run the installer to update a previous test installation.
