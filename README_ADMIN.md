Admin Panel (Updated)
=====================

Files in this package:
- admin_updated.html   -> Admin UI (Excel upload, inline edit, download JSON, upload to GitHub)
- data_preset.json     -> Preset JSON extracted from your uploaded Excel (Give a full excel of all Items in this file.xlsx), contains 807 rows
- README_ADMIN.md      -> This file

How to use:
1. Download and extract the ZIP.
2. Open admin_updated.html in a modern browser.
3. You can either:
   - Click 'Load preset 807 items' to load the included data_preset.json (recommended), or
   - Use 'Choose file' to upload a local Excel (.xlsx/.csv) and edit live.
4. Edit inline, add/delete rows as required.
5. Click 'Download data.json' to save the JSON locally, or provide a GitHub owner/repo/token and click 'Upload to GitHub' to save directly to your repo.

Security notes:
- The GitHub upload requires a Personal Access Token (PAT) with repo or public_repo permission.
- Do not share your PAT. Use a limited-scope token when possible.
- When hosting admin_updated.html on the web, the 'Load preset' button will try to fetch the original Excel path; this only works if the file is hosted/served at that exact path. The packaged data_preset.json is the reliable way to load the preset items.

Preset file path included: /mnt/data/Give a full excel of all Items in this file.xlsx
