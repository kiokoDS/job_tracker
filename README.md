<p align="center">
  <img src="https://job-tracker-gilt-phi.vercel.app/icon.webp" width="96" alt="Job Tracker icon">
</p>

<h1 align="center">Job Tracker: free LinkedIn job tracker for Windows &amp; Linux</h1>

<p align="center">
  A free, open desktop <b>job application tracker</b> that finds new <b>LinkedIn jobs</b> for your
  saved searches and tracks every application from <b>Applied</b> to <b>Offer</b>.<br>
  No account, no subscription, and your data never leaves your computer.
</p>

<p align="center">
  <a href="https://github.com/kiokoDS/job_tracker/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/kiokoDS/job_tracker?label=download"></a>
  <a href="https://github.com/kiokoDS/job_tracker/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/kiokoDS/job_tracker/total"></a>
  <img alt="Platforms" src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue">
  <img alt="Price" src="https://img.shields.io/badge/price-free-brightgreen">
</p>

<p align="center">
  <a href="https://job-tracker-gilt-phi.vercel.app"><b>Website</b></a> ·
  <a href="https://github.com/kiokoDS/job_tracker/releases/latest"><b>Download</b></a> ·
  <a href="#faq"><b>FAQ</b></a>
</p>

---

Job Tracker replaces the spreadsheet you use to keep track of job applications. Tell it what
you're looking for (for example *"mobile developer"* in *"Kenya"*). It pulls matching LinkedIn job
listings every time it opens, and you can move each job through your pipeline with a right-click.

## Features

- **Finds LinkedIn jobs automatically.** It fetches new public LinkedIn job postings for your saved
  search terms and locations every time the app starts. Press *Update Jobs* to check again.
- **Tracks every application.** Each job has a status: New, Applied, Reached Out, Interview, Offer or
  Rejected. The date you applied is recorded automatically.
- **Search and filter.** Find any job by title, company or location. Jobs you remove stay removed.
- **See your progress.** An activity heatmap shows a year of your job search, one square per day.
- **Private and offline-first.** Everything is stored in a local database on your computer.
  There's no sign-up, cloud sync or tracking.
- **Lightweight.** It's a single file with no installer required on Windows, and there's a `.deb`
  package for Ubuntu and Debian.

## Download

Get the latest version from the **[Releases page](https://github.com/kiokoDS/job_tracker/releases/latest)**:

| Platform | File |
|---|---|
| Windows 10 / 11 (64-bit) | [`JobTracker.exe`](https://github.com/kiokoDS/job_tracker/releases/latest/download/JobTracker.exe) |
| Ubuntu / Debian (64-bit) | [`JobTracker-linux-amd64.deb`](https://github.com/kiokoDS/job_tracker/releases/latest/download/JobTracker-linux-amd64.deb) |
| Any Linux (64-bit) | [`JobTracker-linux`](https://github.com/kiokoDS/job_tracker/releases/latest/download/JobTracker-linux) |

### Install on Windows

Double-click `JobTracker.exe`. If Windows shows *"Windows protected your PC"*, click
**More info → Run anyway** (the app isn't code-signed yet).

### Install on Ubuntu / Debian

```sh
sudo apt install ./JobTracker-linux-amd64.deb
```

Then open **Job Tracker** from your app menu, or run `job-tracker` in a terminal.

### Run on any Linux distro

```sh
chmod +x JobTracker-linux
./JobTracker-linux
```

## FAQ

**Is Job Tracker free?**
Yes. It's completely free on Windows and Linux, with no account or subscription.

**How does it find LinkedIn jobs?**
Save your search terms and locations. Job Tracker pulls matching *public* LinkedIn job listings each
time it starts, so you don't need to log in to LinkedIn.

**How do I track the status of a job application?**
Right-click a job (or use *Set Status*) to move it through New → Applied → Reached Out → Interview →
Offer / Rejected.

**Where is my data stored?**
In a local `jobs.db` file next to the app. If that folder is read-only, as with the `.deb` install,
the file goes in your user data folder. Nothing is uploaded.

**Is this a good alternative to a job search spreadsheet, Huntr or Teal?**
If you want a simple, private, offline job application tracker focused on LinkedIn, yes. There's no
browser extension or account to set up.

**Does it work on macOS?**
Not yet. Windows and Linux only for now.

## Support

If Job Tracker helped your job search, you can
[buy me a coffee](https://job-tracker-gilt-phi.vercel.app/#donate) ☕. Found a bug or want a feature?
[Open an issue](https://github.com/kiokoDS/job_tracker/issues).

---

<sub>Keywords: LinkedIn job tracker, job application tracker, job search tracker, job hunt organizer,
application tracking for job seekers, free job tracker app for Windows, job tracker for Linux.</sub>

<sub>Job Tracker is not affiliated with, endorsed by or sponsored by LinkedIn.
LinkedIn is a trademark of LinkedIn Corporation.</sub>
