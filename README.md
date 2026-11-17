# Project: 10 tk — Website

Bengali-first static website for Project: 10 tk, a donation-based charity organisation.
Built from the verified content of its Facebook page (https://www.facebook.com/projecttentk).

- Single file: `index.html` (4.4 MB) — all case photos are embedded, so no
  Facebook CDN link is needed and the images do not expire.
- White background, with cards and text in the light-blue / dark-red / blue /
  red colours from the Facebook page.
- Sections: intro, আমাদের কাজ (cases 655–656 done, 650–654, 645–649, Gaza food
  distribution), September 2026 (৳2,85,000) and October 2026 (৳2,38,000)
  monthly reports, and Donate (bKash/Nagad/Upay 01611498128, bKash Merchant
  01816532793, Bangla QR).

Note: the Rocket number is deliberately left as "নম্বর নিশ্চিত করা বাকি" in the
site until the owner confirms which number is correct — do not publish a
Rocket number from the cover (016114981287) or the post (01611498128) as fact.

## Deploy

- GitHub Pages / any static host: serve `index.html` as-is.
- Vercel: import this repository as a static site (no build command, output
  directory is the repository root).
