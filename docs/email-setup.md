# Company email setup

Target address: `hello@shortstuffplayground.com`

## Recommended setup

Use Google Workspace Business Starter so Junie gets a real Gmail inbox, calendar, Drive storage, spam filtering, and the ability to send and receive as the company address. The standard annual-commitment list price observed September 13, 2026 was $7 per user per month before tax; checkout pricing and promotions can change.

## Work remaining

1. Confirm Junie wants Google Workspace and identify the account owner and recovery phone/email.
2. Start the subscription in the client's name and complete any purchase confirmation.
3. Verify `shortstuffplayground.com` by adding Google's TXT record in Netlify DNS.
4. Add Google's MX records and remove any conflicting MX records.
5. Publish SPF, enable DKIM after activation, and add a monitoring-first DMARC record.
6. Create `hello@shortstuffplayground.com`, secure it with MFA, and store recovery codes with the client.
7. Test inbound mail, outbound mail, replies, spam placement, and contact-form delivery.
8. Change website form notifications from the temporary Yahoo address to the new mailbox after verification.

Mailbox creation requires the client's provider/subscription choice and account-recovery details. No credentials or secrets belong in this repository.
