# WA Bulk Sender — Privacy Policy

_Last updated: 6 October 2026_

WA Bulk Sender is a browser extension that adds a bulk-messaging panel to WhatsApp Web (web.whatsapp.com).

## What data the extension handles

- **Contact lists you paste or upload** (phone numbers, names and any other columns in your sheet).
- **The message text and attachments you compose.**
- **Sending results** (which numbers were sent, failed or skipped, and when).
- **Your unsubscribe list** and your speed settings.

## Where that data goes

All of it stays **on your own computer**, inside the browser's local extension storage. Messages are sent through the WhatsApp Web session that is already open in your browser, directly to WhatsApp's own servers, exactly as if you had typed them.

The extension does not transmit your contacts, messages or reports to the publisher or to any third party, and it contains no analytics, tracking or advertising code. The only information that goes to the publisher is listed in the next section.

## What is sent to the publisher

To run the free trial and paid plans, the extension contacts the publisher's licence service (a Google Apps Script web app backed by a private Google Sheet):

- **Plan check**, when WhatsApp Web connects and a few times a day after that: your WhatsApp number, your WhatsApp display name, the extension version, and four usage counts (how many campaigns you have run and how many messages, replies and follow-ups in total). This is how the trial and your paid plan are tied to your number. No contact details or message text are included.
- **Payment form**, only when you submit it: your WhatsApp number, the plan you chose and the payment reference number you typed.
- **Support form**, only when you submit it: your WhatsApp number, your message and, if you leave the box ticked, technical details (extension version, WhatsApp Web version, browser version, plan status).

Your contact lists, the messages you send and your reports are never sent to the publisher. This information is used only to manage your plan and answer your support requests, and is not sold or shared.

The only other network request the extension makes is:

- **Google Sheets import**, only when you paste a sheet link and click Import. The sheet is downloaded as CSV from docs.google.com directly into your browser, using your own Google login. Nothing is sent to Google other than that download request, and the extension never writes to your sheets.

## Permissions

- **Access to web.whatsapp.com** — needed to add the panel to WhatsApp Web and to send messages through it. The panel does not run on any other site.
- **Access to docs.google.com and googleusercontent.com** — only to download a Google Sheet you chose to import.
- **Access to script.google.com** — the plan check, payment form and support form described above.
- **Storage / unlimited storage** — to keep your settings, contact lists, templates, unsubscribe list and campaign history with results on your device, without hitting the browser's default 10 MB limit on large lists.

## Deleting your data

Clear the run with the **Clear** button in the panel, or remove the extension from `chrome://extensions`. Removing the extension deletes everything it stored.

## Your responsibility

You are responsible for having the right to message the people on your lists and for following WhatsApp's terms and the laws that apply to you (for example consent and anti-spam rules). The extension includes an unsubscribe list and automatic STOP handling to help with that.

## Contact

Questions: open an issue at https://github.com/vaibhavvijay10/wa-bulk/issues
