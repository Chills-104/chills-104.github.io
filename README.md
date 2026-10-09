Energy Monitor – project site
This repository hosts the public home page and privacy policy for Energy Monitor, a personal home-energy tool. The pages are published with GitHub Pages and are linked from the app's Google OAuth consent screen.
Home page: https://chills-104.github.io/
Privacy policy: https://chills-104.github.io/privacy.html
What Energy Monitor is
A small add-on for Home Assistant that I run at home. Every night it collects my household's solar production, home-battery state, grid import/export, electricity prices and weather, checks the day for problems, and sends me a short daily report. It helps me judge how my solar panels, battery and dynamic electricity tariff work together.
How it uses Google Drive
The add-on copies its own data exports (data tables and daily report texts) into one folder in my own Google Drive, so I can read and analyse them from other devices. It requests only the `drive.file` permission, which limits it to files and folders the add-on itself creates. It does not read my Drive, profile, email or contacts.
Not a public product
This is a single-user tool. It is not offered to other people and only my own Google account authorises it. The add-on's source code is not published here.
Files in this repository
File	Purpose
`index.html`	Home page describing the app
`privacy.html`	Privacy policy
`README.md`	This file (not part of the published site)
Contact
Carl Hills, kortenakenhills@gmail.com
