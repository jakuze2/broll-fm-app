# Broll FM — capture app

The installable web app used by Broll facilities staff at the World Bank
headquarters in Kampala: stock movements, cleaning rounds, meter readings.

This repository holds the **app shell only** — screens and logic, no data.
Records live on the device until they sync to a private server behind a login.

`task.html` is the single-job sheet an outside contractor opens from a one-time
link. It shows one job, accepts one submission, and then the link is dead.

`install.html` is the Android download page — see the Releases tab for the APK.

Live: https://jakuze2.github.io/broll-fm-app/
