# Tools downloads

Free downloads of small tools by Tomasz Otto. No GitHub account needed: click a link and the file downloads.

Everything runs locally on your own computer. Nothing is uploaded anywhere.

## Disclaimer: please read

- These are **personal side projects** by Tomasz Otto. They are **not official company software** and are not supported by any employer or IT department.
- They are provided **"as is", without warranty of any kind**, express or implied.
- **Use them at your own risk.** The author is **not liable for any loss or damage**, including lost or damaged files, arising from their use.
- **Check your organisation's IT rules before installing or running anything.** If in doubt, ask your IT team first.
- **Test on copies of your files first**, never on the only copy.

## Status key

| Status | Meaning |
|---|---|
| **Ready** | Tested and in regular use. |
| **Beta** | Works, but not fully tested. Expect rough edges. |
| **Pilot** | Early version being tried out on real work. Feedback welcome. |
| **Fix pending** | A fix has been made but not yet tested. |
| **Waiting for IT approval** | May be flagged by antivirus. Do not run on a company laptop until your IT approves it. |
| **Self-hosted** | A server or command-line app for technical users, run on your own machine. |

## File Renamer

**Status: Ready**

Bulk-renames files in a folder, either with a numbered prefix (like `MN-01 - Title.pdf`) or from the columns of a CSV register. It shows a preview and renames nothing until you type YES.

- **Download:** [file-renamer-v1.0.0.zip](https://github.com/SYS-TomaszOtto/tools-downloads/releases/download/file-renamer-v1.0.0/file-renamer-v1.0.0.zip)
- **How to run:** unzip, open Windows PowerShell in the folder and run `.\scripts\RenameFilesV2.ps1` or `.\scripts\Rename-FromCsv.ps1`.

## File Mapper

**Status: Ready**

A single web page that maps any folder you pick as a mind map, size treemap, explorer or searchable table, with previews and smart categories.

- **Download:** [File-Mapper.html](https://github.com/SYS-TomaszOtto/tools-downloads/releases/download/file-mapper-v1.0.0/File-Mapper.html) (or the [zip with README and licence](https://github.com/SYS-TomaszOtto/tools-downloads/releases/download/file-mapper-v1.0.0/file-mapper-v1.0.0.zip))
- **How to run:** double-click `File-Mapper.html` to open it in Edge or Chrome, then click **Choose folder**.

## Pathway Pro

**Status: Ready**

A single web page for tracking evidence and skills towards professional registration, and producing reports from them.

- **Download:** [latest Pathway Pro release](https://github.com/SYS-TomaszOtto/pathway-pro/releases/latest) (download `Pathway-Pro.zip`)
- **How to run:** unzip and follow the "How to use Pathway Pro" guide attached to the same release.

## File Browser

**Status: Fix pending, not yet tested**

Browse and full-text search your OneDrive or any local folder in Edge, using a small local PowerShell helper. This version includes a crash fix that has not been tested yet.

- **Download:** [file-browser-2026.11.23.zip](https://github.com/SYS-TomaszOtto/tools-downloads/releases/download/file-browser-2026.11.23/file-browser-2026.11.23.zip)
- **How to run:** unzip and double-click `app\Start Indexed Browser.cmd`; keep its PowerShell window open while you use the Edge tab.

## Keystroke Visualiser (KeyVis Pro)

**Status: Waiting for IT approval.** May be flagged by antivirus; do not run on a company laptop until your IT approves it.

Shows your keystrokes and mouse clicks on screen, with a drawing overlay, for screen sharing and demos. Pause or quit it before typing anything confidential.

- **Download:** [key-vis-pro-v1.0.0.zip](https://github.com/SYS-TomaszOtto/tools-downloads/releases/download/key-vis-pro-v1.0.0/key-vis-pro-v1.0.0.zip)
- **How to run:** unzip, open Windows PowerShell in the folder and run `.\scripts\KeyViz.ps1` (Ctrl+Alt+Q quits).

## Mouse Jiggler

**Status: Beta**

Keeps the PC awake during long manual tasks, so the VPN doesn't drop when the screen locks or you are logged off. Use it only within your organisation's rules.

- **Download:** [mouse-jiggler-v1.0.0.zip](https://github.com/SYS-TomaszOtto/tools-downloads/releases/download/mouse-jiggler-v1.0.0/mouse-jiggler-v1.0.0.zip)
- **How to run:** unzip, open Windows PowerShell in the folder, run `.\scripts\MouseJiggler.ps1` and click **Start Jiggler**.

## Coming later

These are still being prepared for public release: CAD QA, Team Resource Planner and a MicroStation CAD automation toolkit.

## Licence

Everything here is released under the [MIT licence](LICENSE), copyright 2026 Tomasz Otto. The MIT licence includes the no-warranty and no-liability terms above. Each zip may also include its own licence file.
