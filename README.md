# greenleafemail.com

Dedicated email-sending domain for [greenleafassurance.com](https://greenleafassurance.com).

## Why a separate domain

Email deliverability (SPF/DKIM/DMARC records, sender reputation, spam-list risk) is
kept isolated on `greenleafemail.com` so it can never affect the DNS health, security
posture, or search ranking of the main site, `greenleafassurance.com`. This domain is
not meant to be browsed — it exists purely to send and authenticate mail.

## This repo

Just a single static parking page (`index.html`). If someone lands here by accident,
it shows a black page with a short note pointing them to the main site.

No build step, no dependencies — deploy the static file as-is.
