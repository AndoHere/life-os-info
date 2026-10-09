---
title: Life OS privacy policy
layout: default
permalink: /privacy/
---

# Life OS privacy policy

Last updated: 9 October 2026

Life OS is a personal app used by one person on their own devices. This policy explains what happens to data when someone uses it.

## What the developer collects

Nothing. Life OS has no server run by the developer, no analytics, no advertising and no tracking. The developer never receives your notes, files, email addresses or Google account data.

## Where your data lives

- Your notes, tasks and settings are stored as ordinary files on your own laptop and phone.
- They are synchronised through a private GitHub repository that you own and control, using a GitHub access token that you create. On the phone the token is kept in the Android Keystore. On the laptop it is kept by your operating system's credential manager.
- If you sign in with Google, files the app creates are stored in your own Google Drive.

## Google user data

Life OS requests only the `https://www.googleapis.com/auth/drive.file` scope. With it the app can read, create, change and delete only the files that Life OS itself created in your Google Drive. It cannot access any other file in your Drive.

- The app uses this access only to store and retrieve those files for you.
- Google data is not sent to the developer or to any third party, is not sold, and is not used for advertising or to train machine-learning models.
- Access tokens are used on your device and are not written to logs or to your notes.

The use of information received from Google APIs follows the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Other services you may connect

If you choose to connect Life OS notes to Claude, Gmail or Google Calendar through Anthropic's own connectors, that happens inside your Anthropic account under Anthropic's terms and privacy policy, not through Life OS.

## Deleting your data

Delete the files in your GitHub repository and your Google Drive, and revoke the app's access at [myaccount.google.com/permissions](https://myaccount.google.com/permissions) and in your GitHub token settings. Uninstalling the app removes its local data.

## Changes and contact

If this policy changes, the date above will change. Questions: open an issue at [github.com/AndoHere/life-os-info/issues](https://github.com/AndoHere/life-os-info/issues).
