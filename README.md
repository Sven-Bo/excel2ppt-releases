# Excel2PPT Add-in 1.0.0

Export Excel ranges, tables and charts to PowerPoint from a dedicated Excel ribbon. Your export setup stays in your workbook, which can remain an ordinary `.xlsx` file.

[Download the Windows installer](https://pythonandvba.com/go/excel2ppt-addin-download)

## Install

1. Save your work and close Excel.
2. Run **Excel2PPT-Setup.exe** and choose **Install Excel2PPT**.
3. Open Excel and select the **Excel2PPT** ribbon tab.

Setup installs for your Windows user. Run a newer installer to update. Remove the add-in through Windows Installed Apps.

Requires desktop Excel and desktop PowerPoint on 64-bit Windows, with .NET Framework 4.8 or later. Both 32-bit and 64-bit Excel are supported by the package. Mac, Excel for the web and native ARM64 Office are not supported. The installer includes its own runtime; WebView2 is not required.

The installer is currently unsigned. Windows or your organization's policy may prevent installation.

## Try your first export

1. Open a blank workbook and save it.
2. Click **Excel2PPT > Demo > Add demo sheet**. It adds sample data and a short tutorial, plus example rows in **PPT Setup**.
3. The three picture examples are enabled and ready to export in Free. The optional Pro text row stays disabled.
4. In **Settings**, choose **New presentation**, then save the settings.
5. Click **Export**. Review the new PowerPoint file.

For your own workbook, click **Create setup**, select cells or a chart, and click **Add selection**. Source dropdowns also find tables, named ranges, charts and shapes. Click **Refresh sources** after creating or renaming these objects.

## Find the example files

Choose **Excel2PPT > Demo > Open demo workbook** to try a quarterly business review with fictional sales data, live calculations, native charts and five prepared export rows. It works in Free immediately. **Open examples folder** also contains a completed presentation and a matching optional Pro template. The workbook includes instructions for each. This is separate from the small tutorial that **Add demo sheet** inserts into your current workbook.

On first use, the add-in copies the examples to **Documents > Excel2PPT > Examples > Business review**. Later clicks reopen your working copy and preserve your edits. Choose **Create fresh demo copy** to start again in a separate folder. The installer also offers **Open examples folder** after installation.

## Set up an export

| Column | What to enter |
| --- | --- |
| Source | Choose an Excel object, or enter the replacement text/cell for a text row. |
| Name / placeholder | An object label, or the exact PowerPoint placeholder such as `{{REVENUE}}`. |
| Slide | The destination slide number. For text replacement, leave blank to search every slide. |
| Left, Top, Height, Width | Optional dimensions in points. Leave blank to fit automatically. Dimension Finder can copy these from a selected PowerPoint object. |
| Paste as | Picture, Editable chart, Linked chart, Text from cell, or Fixed text. Editable and linked modes require charts. |
| Export | Yes to include the row; No to skip it. |

Save the workbook to keep its setup. Settings lets you choose an output folder and filter the source dropdowns. Local folders, locally synced OneDrive files and accessible network shares can be used. For workbooks opened from a web URL, choose an explicit local or network output folder.

## Free and Pro

**Free** exports up to five enabled picture rows per export to a new presentation, with setup, source discovery, positioning and Dimension Finder included. No watermark is added.

**Pro and Team** include unlimited pictures per export, PowerPoint templates, editable and linked charts, text replacement and updating the active presentation. Active-presentation export changes the open deck directly; review it and save in PowerPoint.

Personal covers one user on up to three devices. Team covers up to 15 users on 15 devices in total. Both paid plans have the same features. Enter your 21-character purchase key under **License** to activate Pro.

[Get Excel2PPT Pro](https://pythonandvba.com/go/excel2ppt-addin-checkout)

## Help

Expected setup issues show instructions for fixing them. Unexpected failures include technical details you can copy when contacting support. Do not post license keys or private workbook data in public issues.

This repository distributes the compiled installer, checksums and release notes. Application source code is not published. Third-party notices are included in the installation.
