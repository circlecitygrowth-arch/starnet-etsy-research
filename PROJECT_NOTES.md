# Project notes

## Why this exists

My product research was turning into too many browser tabs and scattered notes. The goal is not to collect everything on Etsy. I want a small routine that answers a narrower question: is this product category worth making an original prototype for?

## First working milestone

The first useful version should let me:

1. choose one product phrase or category;
2. retrieve a limited set of public listing fields through Etsy's Open API;
3. compare the results in a consistent format;
4. write and save my own observations; and
5. stop without creating or changing an Etsy listing.

## Decisions already made

- One user only.
- Read-only research first.
- No page scraping.
- No public signup or seller-facing service.
- No copying listing text, images, downloads, branding, or product designs.
- API credentials stay outside the repository.
- I review the research and approve product decisions myself.

## Still to decide after API approval

- The exact API resources and OAuth scopes required.
- Which fields are useful enough to retain.
- Whether research notes should be kept locally or in a private database.
- A clear retention period for any saved API-derived data.
- The smallest useful comparison view.

I will update these notes as those decisions are tested. I would rather leave an item plainly unfinished than describe a feature that does not exist yet.
