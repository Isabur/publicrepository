# Privacy Policy

Last updated: 2026-09-22

This application ("gmail-attachments") is a personal command-line tool, used only by its
author on their own computer to download attachments from their own Gmail mailbox.

## What data is accessed

The app requests a single OAuth scope, `https://www.googleapis.com/auth/gmail.readonly`.
It uses this scope solely to retrieve one attachment at a time, identified by a message ID
and an attachment ID supplied by the user. It cannot send, modify or delete messages.

## How data is handled

- Downloaded attachments are written to a local file path chosen by the user.
- OAuth credentials are stored locally on the user's own machine and are not shared.
- No data is transmitted to any third party, server or analytics service. There is no
  backend — the app talks only to Google's API.
- No data is retained by the developer, because the developer receives no data.

## Contact

Questions can be raised as an issue in this repository.
