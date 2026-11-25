# Ryu privacy policy

Last updated: November 25, 2026

Ryu is a web browser for Windows made by DragoncyK. This page explains what Ryu does with your data.
In short: **Ryu has no servers and no accounts. Everything you do in Ryu stays on your PC**, and Ryu never
sends anything about you to its creator.

## What stays on your PC

Ryu keeps these on your computer only, in your Windows user folder:

- Your history, tabs, spaces, notes, pinned tabs, downloads list and settings.
- Cookies and site data of the websites you visit.
- Saved passwords, encrypted with your Windows account (and, if you turn it on in Settings, also with
  your master password or Windows Hello).
- A backup of your settings, tabs, notes and saved passwords from the last few days (never your
  history), used only to repair Ryu's data if it gets damaged. Deleting data deletes the backups too.
- A log of errors, which contains no web addresses, passwords or page content.

You can delete any of it in Settings, and uninstalling Ryu removes the program (your data folder can be
deleted too).

## When Ryu connects to the internet by itself

Besides the websites you open, Ryu connects to:

| What | Who | When | What is sent |
| --- | --- | --- | --- |
| Search suggestions | The search engine you choose (Google, DuckDuckGo, Brave or Startpage) | While you type in the address bar | What you type |
| Dangerous-site lists | malware-filter (GitLab) | About once a day | Nothing about you |
| Ad and tracker block lists | Ghostery's public lists | Now and then | Nothing about you |
| Updates | GitHub (github.com/DragoncyK/ryu) | When Ryu opens and every few hours | The usual request for a file |
| Protected video (Widevine) | Google | The first time it is needed | The usual request for the component |
| Secure DNS | Cloudflare or Google | Only if you turn it on | The names of the sites you visit |
| Translate a page | Google Translate | Only when you ask | The address of the page |
| Password leak check | Have I Been Pwned | Only when you ask | The first 5 characters of a hash of each password, never the password |
| Extensions | Chrome Web Store (Google) | Only if you install extensions | The usual requests to the store |

None of these requests carry your Ryu data, your saved passwords or your browsing history, and the update,
list and leak checks are made without your cookies.

## What Ryu never does

- No analytics, no telemetry, no advertising and no tracking.
- No selling or sharing of data: Ryu's creator receives nothing about you.
- Problem reports are only sent if you choose **Settings → Report a problem**: Ryu opens a public report
  on GitHub, already cleaned of addresses, names, emails and keys, and you read it and send it yourself.

## Websites and extensions

Websites you visit and extensions you install have their own privacy policies. Ryu blocks known trackers,
dangerous sites and third-party cookies by default, but it cannot control what a website does with what you
give it.

## Children

Ryu is a general-purpose web browser and does not collect any data, from anyone.

## Changes and contact

If this policy changes, the new version is published on this page. For questions, open an issue at
github.com/DragoncyK/ryu/issues.
