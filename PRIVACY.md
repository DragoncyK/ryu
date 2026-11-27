# Ryu privacy policy

Last updated: November 27, 2026

Ryu is a web browser for Windows made by DragoncyK. This page explains what Ryu does with your data.
In short: **Ryu has no servers and no accounts. Everything you do in Ryu stays on your PC**, and Ryu never
sends anything about you to its creator.

## What stays on your PC

Ryu keeps these on your computer only, in your Windows user folder:

- Your history, tabs, spaces, notes, pinned tabs, downloads list and settings.
- Only if you turn on "Search in pages you read" (Settings › Privacy; it is off unless you do): the text
  of the pages you read, so the search bar can find a page by what it said. Ryu never keeps it for
  private spaces, files on your PC, sites where you turned shields off, sites you are signed in to,
  mail, chat and document apps (such as Gmail, Outlook, Google Docs, WhatsApp or Slack), pages on your
  home or work network, or pages that look like a sign-in, account, bank or checkout page or that have
  a password or card field. It is deleted with
  your history (all of it, by period, or page by page), after 90 days like your history, and on its own
  when you turn the setting off and choose to delete it.
- Cookies and site data of the websites you visit.
- Saved passwords and two-step verification keys, encrypted with your Windows account (and, if you turn
  it on in Settings, also with your master password or Windows Hello).
- The picture you choose for the start page, if any (a smaller copy of it).
- A backup of your settings, tabs, notes and saved passwords from the last few days (never your
  history or the text of pages you read), used only to repair Ryu's data if it gets damaged. Deleting
  data deletes the backups too.
- A log of errors, which contains no web addresses, passwords or page content.
- If Ryu closes unexpectedly, a crash file that can help find the cause. Only the last five are kept,
  and Ryu never sends them; they may hold pieces of the pages that were open.

Importing from another browser reads that browser's files on your PC, and exporting writes a file where
you choose. Neither sends anything anywhere.

You can delete any of it in Settings, and uninstalling Ryu removes the program (your data folder can be
deleted too).

## When Ryu connects to the internet by itself

Besides the websites you open, Ryu connects to:

| What | Who | When | What is sent |
| --- | --- | --- | --- |
| Search suggestions | The search engine you choose (Google, DuckDuckGo, Brave or Startpage) | While you type in the address bar | What you type |
| Dangerous-site lists | malware-filter (GitLab) | About once a day | Nothing about you |
| Ad, tracker and cookie-notice block lists | Ghostery's public lists (GitHub) | About once a week | Nothing about you |
| Currency rates | European Central Bank, through frankfurter.app | Only when you type a currency conversion in the address bar | Nothing about you |
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
  If a crash file exists, Ryu can show it to you; attaching it is up to you.

## Websites and extensions

Websites you visit and extensions you install have their own privacy policies. Ryu blocks known trackers,
dangerous sites and third-party cookies by default, but it cannot control what a website does with what you
give it.

## Children

Ryu is a general-purpose web browser and does not collect any data, from anyone.

## Changes and contact

If this policy changes, the new version is published on this page. For questions, open an issue at
github.com/DragoncyK/ryu/issues.
