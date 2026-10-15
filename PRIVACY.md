# Privacy Policy: Request Board for Gmail

_Last updated: 14 October 2026_

## Short version

Request Board for Gmail keeps everything on your own computer. It does not collect, send, sell or share any data. It has no servers, no accounts, no analytics and no tracking.

## What the extension stores

Only when you click **Add to requests** on an open email, the extension saves these details about that one email:

- Sender name and email address
- Email subject
- Gmail thread ID and the Gmail account number in the address (u/0, u/1, …), so "Open email" can reopen it
- The date and time you added it, and its current stage (New, Waiting for resource, Sent)
- Any short note you type yourself

It also keeps cards you removed for 30 days (so you can restore them), then deletes them.

It never reads the body of any email, attachments, or any other email, and it never scans your inbox.

## Where it is stored

In your browser's local extension storage (`chrome.storage.local`) on this computer only. It is not synced to your Google account and is not sent anywhere.

If you use **Export backup**, a JSON file is saved to your computer. What you do with that file is up to you.

## What is sent over the internet

Nothing. The extension makes no network requests. The only exception is if you click **Buy me a coffee**: that opens the developer's payment page in a new tab, like any normal link. No data from the extension is sent with it.

## Deleting your data

- Remove a card, then **Delete permanently** in "Recently removed".
- Or uninstall the extension. Chrome deletes all of its stored data.

## Children

This extension is not directed at children and collects no personal information from anyone.

## Changes

If this policy changes, the new version will be published at this same address with a new date.

## Contact

Questions: _[add your email address here]_

---

## Chrome Web Store dashboard answers

Copy these into the **Privacy** tab of the developer dashboard.

### Single purpose

> Request Board for Gmail lets a user manually save an open Gmail email to a simple three-stage board (New, Waiting for resource, Sent) in Chrome's side panel, to keep track of email requests until they are answered.

### Permission justifications

**storage**
> Saves the user's board (the emails they chose to add, their stage, and optional notes) locally on the device with chrome.storage.local. Nothing is synced or sent anywhere.

**sidePanel**
> Displays the board in Chrome's side panel when the user clicks the toolbar icon, so it does not cover or resize Gmail.

**Host permission: https://mail.google.com/\***
> Needed to add a single "Add to requests" button to Gmail's toolbar. When the user clicks it, the extension reads the open email's subject, sender name and address, and thread ID from that page so it can create the card. It is also used so "Open email" can reopen the thread in the user's current Gmail tab. The extension does not read email bodies, does not scan the inbox, and runs on no other site.

**Remote code**
> No, I am not using remote code. All code is included in the package.

### Data usage (tick these)

- Personally identifiable information: **Yes**, the sender's name and email address of emails the user chooses to add (stored locally only).
- Website content: **Yes**, the subject line of emails the user chooses to add (stored locally only).
- All other categories (health, financial, authentication, personal communications content, location, web history, user activity): **No**.

Certify:
- I do not sell or transfer user data to third parties, outside of the approved use cases.
- I do not use or transfer user data for purposes that are unrelated to my item's single purpose.
- I do not use or transfer user data to determine creditworthiness or for lending purposes.
