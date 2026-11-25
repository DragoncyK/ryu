# Ryu

A web browser for Windows with spaces, a sidebar, split view and a mini player. Made by **DragoncyK**.

## Install

1. Open the [latest release](https://github.com/DragoncyK/ryu/releases/latest).
2. Under **Assets**, download `Ryu-Setup-<version>.exe`.
3. Open it. If Windows warns about an unknown publisher, choose **More info → Run anyway**
   (the installer doesn't carry a paid certificate yet; the warning only shows this once).
4. Pick where to install it and you're done. No administrator rights needed.

## Updates

Ryu updates itself: it looks for new versions when it opens and every few hours, downloads them in the
background and shows **Update** in the sidebar. If you don't click it, the update installs when you close Ryu.

Every version is signed by its creator. Before installing anything, Ryu checks that signature; a version that
is unsigned or has been changed is deleted and never installed.

If a version ever fails to start, Ryu offers to look for a newer one and installs it by itself. If its data
gets damaged, it sets the damaged copy aside and brings back its latest backup.

## Problems and ideas

In Ryu, open **Settings → Report a problem**. Ryu opens a new issue here, already filled in with its version
and its recent error messages (with web addresses, names, emails and keys removed). Write what happened and
send it; you see everything before sending. Issues are public, so please leave out personal details.

## Privacy

- Ryu has no servers and no accounts: your history, tabs and passwords stay on your PC. Nobody else who
  uses Ryu can see anything of yours, and Ryu opens no connection that other computers could reach.
- Passwords are stored encrypted with your Windows account, and copying one asks for Windows Hello. In
  Settings you can also lock them with a master password (opened with Windows Hello too), so that not even
  a program running on your PC can read them.
- Ryu keeps backups of your settings, tabs, notes and saved passwords (still encrypted) from the last few
  days, to repair its data if needed. Browsing history is never in them, and deleting data deletes them too.
- Besides the websites you open, Ryu only reaches the internet for: suggestions from the search engine you
  choose, public lists of dangerous sites, updates from this repository and, if you ask, whether a password
  appears in known data leaks (without ever sending the password).

This repository only holds the installers; Ryu's source code is not public.
