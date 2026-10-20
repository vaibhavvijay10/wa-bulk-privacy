# WA Bulk Sender — Privacy Policy

_Last updated: 20 October 2026_

WA Bulk Sender is a browser extension that adds a bulk-messaging panel to WhatsApp Web (web.whatsapp.com).

## What data the extension handles

- **Contact lists you paste or upload** (phone numbers, names and any other columns in your sheet).
- **The message text and attachments you compose.**
- **Sending results** (which numbers were sent, failed or skipped, and when).
- **Replies from the people you messaged.** The extension reads them inside your browser to count replies, to stop follow-ups to people who answered, and to honour "STOP" requests. They are never sent anywhere.
- **Your unsubscribe list** and your settings.

## Where that data goes

All of it stays **on your own computer**, inside the browser's local extension storage. Messages are sent through the WhatsApp Web session that is already open in your browser, directly to WhatsApp's own servers, exactly as if you had typed them.

The extension does not transmit your contacts, messages, replies or reports to the publisher or to any third party, and it contains no analytics, tracking or advertising code. The WhatsApp library it includes (wa-js) has optional usage analytics and an optional outside link-preview service; WA Bulk Sender switches both off, so link previews are made by WhatsApp itself. The only information that goes to the publisher is listed in the next section.

## What is sent to the publisher

To run the free trial and paid plans, the extension contacts the publisher's licence service (a Google Apps Script web app backed by a private Google Sheet):

- **Plan check**, when WhatsApp Web connects and about once an hour while it stays open: your WhatsApp number, your WhatsApp display name, the extension version, and a few usage counts (how many campaigns you have run; how many messages, replies and follow-ups in total; and how many times you opened the panel, added a contact list and sent yourself a test message). If parts of WhatsApp Web that the extension relies on fail to load, the names of those parts are included so the problem can be fixed. This is how the trial and your paid plan are tied to your number. No contact details, message text or replies are included.
- **Payment form**, only when you submit it: your WhatsApp number, the plan you chose and the payment reference number you typed.
- **Support form**, only when you submit it: your WhatsApp number, your message and, if you leave the box ticked, technical details (extension version, WhatsApp Web version, browser version, operating system, plan status and how many campaigns you have).

This information is used only to manage your plan, keep the service working and answer your support requests. It is not sold or shared.

The only other network request the extension makes is:

- **Google Sheets import**, only when you paste a sheet link and click Import. The sheet is downloaded as CSV from docs.google.com directly into your browser, using your own Google login. Nothing is sent to Google other than that download request, and the extension never writes to your sheets.

## Permissions

- **Access to web.whatsapp.com** — needed to add the panel to WhatsApp Web and to send messages through it. The panel does not run on any other site.
- **Access to docs.google.com and googleusercontent.com** — only to download a Google Sheet you chose to import.
- **Access to script.google.com** — the plan check, payment form and support form described above.
- **Storage / unlimited storage** — to keep your settings, contact lists, templates, unsubscribe list and campaign history with results on your device, without hitting the browser's default 10 MB limit on large lists.

## Deleting your data

Delete campaigns from the Campaigns list, clear loaded contacts with the **Clear** button, or remove the extension from `chrome://extensions`; removing it deletes everything it stored on your computer. To have your plan record (number, name, usage counts, payment and support messages) deleted from the publisher's records, email vvvj.14@gmail.com from any address and include the WhatsApp number.

## Your responsibility

You are responsible for having the right to message the people on your lists and for following WhatsApp's terms and the laws that apply to you (for example consent and anti-spam rules). The extension includes an unsubscribe list and automatic STOP handling to help with that.

## Contact

Email vvvj.14@gmail.com, or WhatsApp +91 99822 67285.
