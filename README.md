# content-assets

Public hosting for [`content-system`](https://github.com/DD-PLAY-AI/content-system)
(which is private). Two jobs, one reason:

- `cards/` — card-news images. Meta's Graph API does not accept file uploads;
  it fetches the image from a public HTTPS URL server-side, so the images have
  to live somewhere public before a post can go out.
- `review/` — per-batch review pages. The operator opens these on a phone to
  see the image and the copy together. Approving and rejecting happens in
  Telegram, not here; these pages are read-only.

Served by GitHub Pages from `main`.

## Everything here is public

Only material that is about to be posted publicly anyway belongs in this repo.
No source, no tokens, no ledger, no drafts that have been rejected.
