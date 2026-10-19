# rclone-oauth

The home page and privacy policy for a personal, single-user Google OAuth client. The client lets [rclone](https://rclone.org) copy an encrypted backup from a home server to the owner's own Google Drive.

Google asks every OAuth client for a public home page and a privacy policy, so this repository publishes them with GitHub Pages:

- Home: https://janitorhead.github.io/rclone-oauth/
- Privacy policy: https://janitorhead.github.io/rclone-oauth/privacy.html

There is no code here, and the client is not a public service: it is not offered to anyone else and does not access anyone else's data.

## Doing the same for your own rclone

rclone's shared Google client is rate-limited. Its docs recommend [making your own client ID](https://rclone.org/drive/#making-your-own-client-id). If you publish your app as "In production" rather than "Testing", Google wants a home page and privacy policy like these; copy the two HTML files and change the wording to match your setup.
