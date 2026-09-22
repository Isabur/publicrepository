# publicrepository

# gmail-attachments

A small personal command-line tool that downloads a single attachment from the owner's own
Gmail mailbox through the official Gmail API.

It is used privately by its author only. It requests exactly one OAuth scope,
`https://www.googleapis.com/auth/gmail.readonly`, and can therefore only read — it cannot
send, modify or delete anything. Downloaded files are written to the local machine; no data
is transmitted anywhere else.

See [PRIVACY.md](PRIVACY.md) for the privacy policy.
