This macro watches only new, unread messages delivered to Outlook (even if rules move them into vendor folders) and, when they’re sent to a specific mailbox, saves invoice‑related attachments to a network path.
It’s tuned for low overhead: it requires an attachment first, then checks sender email + subject + body for keywords before touching filenames or file contents.
