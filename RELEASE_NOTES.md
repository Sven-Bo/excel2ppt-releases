# Excel2PPT Add-in 1.0.0

Export Excel ranges, tables and charts to PowerPoint from the Excel2PPT ribbon. This update remains version **1.0.0**.

- One workbook setup table with source dropdowns and export options.
- Compact settings with full-width file paths and consistent Browse buttons.
- New slide layout has hover guidance explaining PowerPoint placeholders and why Blank is recommended for Excel exports.
- Documentation and About sit together in the ribbon Help group. About includes the installed version, documentation, support and website links, plus a copyright credit for Bosau Digital L.L.C.
- Saved-export success messages include Open folder alongside Done, while keeping review warnings visible.
- Output names can be fixed or read from a single cell or named range, with a filename preview in Settings. Each export reads the current cell result. Missing cells, formula errors and invalid filenames show clear guidance before export.
- Settings labels templates and active-presentation updates as Pro for Free users, explains the requirement immediately, and prevents saving those destinations until Pro is active.
- Export checks identify the specific Pro feature in use, such as templates, editable charts, linked charts or text replacements, with a matching fix.
- Free exports up to **five enabled picture rows** to a new presentation, with no watermark or time limit.
- The mini tutorial and bundled business workbook work in Free by default.
- New mini tutorial sheets place Total revenue directly below the single-cell heading. Existing demo sheets and edits are preserved.
- A quarterly business review includes fictional sales data, live formulas and five prepared export rows across four slides. Two borderless native Excel charts share one slide, with a shorter Start here guide.
- The demo PPT Setup table now has consistent borders, native alternating row shading and header filters, with wider placement columns.
- A completed business presentation and matching optional Pro template replace the old template files in the installer.
- Fixed the missing embedded images for the examples folder and fresh-copy commands in the Demo menu.
- Dimension Finder with two-decimal placement values and corrected sizing after monitor DPI changes, without needing to click a button first.
- Export preflight, clear setup guidance and highlighted review warnings.
- Free/Pro comparison now labels Pro picture exports Unlimited, with a gold upgrade crown and a single Get Pro checkout.
- License activation with Personal and Team device allowances.
- Active licenses now have a green status panel. The encrypted saved key is restored masked when reopening License, with an option to reveal it. Deactivate license replaces Use Free and confirms removal from this computer.
- Fixed overlapping license-window controls after activation. Updates now return to the dialog's own UI thread and DPI context, and unsuccessful checks keep the entered key available for retry.
- License checks use a dedicated TLS 1.2 connection so older Excel host networking settings do not block valid keys. Connection failures show verification guidance instead of implying the key is invalid.

Pro adds unlimited pictures per export, templates, editable and linked charts, text replacement and updating the open presentation. Personal and Team have the same features. Exceeding the Free limit stops the export and explains how to reduce the selection or upgrade.

## Install or update

Save your work, close Excel, and run **Excel2PPT-Setup.exe**. Reopen Excel and select **Excel2PPT > Demo > Open demo workbook**. Click **Export** for its first four-slide presentation. If you already opened an earlier demo, choose **Create fresh demo copy** to get the updated layout while keeping your previous files. Run this installer to update an earlier 1.0.0 installation.

Requires desktop Excel and PowerPoint on 64-bit Windows, with .NET Framework 4.8 or later. Both 32-bit and 64-bit Excel payloads are included. This installer is unsigned; Windows or organization policy may block it.

## Demo menu and working copies

**Add demo sheet** inserts a small tutorial into your current workbook. **Open demo workbook** opens the complete business example. Its workbook, template and completed presentation are copied together into **Documents > Excel2PPT > Examples > Business review**. Reopening preserves edits; **Create fresh demo copy** uses a separate folder. Older Demo folders are kept. The installer opens the same examples location.

Automated entitlement, file-handling, package and isolated dialog checks are used for this build. Business workbook formulas and saved source mappings are verified, and presentation files are structurally checked and rendered. Live Office export, clean-machine installation and purchase/refund verification have not been performed for this build.
