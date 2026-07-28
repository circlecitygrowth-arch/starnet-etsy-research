# StarNet Etsy Research

This is a small personal project I am building while I plan an Etsy shop. I wanted a repeatable way to compare selected public listing details and keep my own research notes instead of working from a pile of browser tabs.

The tool is for my use only. It has no public signup, customer accounts, or shared Etsy credentials.

**Project page:** https://circlecitygrowth-arch.github.io/starnet-etsy-research/

## Current status

Early prototype. My Etsy API application is pending personal approval.

Right now this repository contains the public project page and documentation. After API access is approved, I will connect and test the research workflow, then document the exact resources, scopes, and retention rules used by the working version. I am keeping that distinction explicit rather than pretending the unfinished parts already exist.

## The routine I am building

1. Choose one product phrase or category.
2. Retrieve the public listing fields neded for that comparison through Etsy's Open API.
3. Review practical details such as price, category, personalization choices, and listing structure.
4. Write my own notes and decide whether an original product idea is worth prototyping.

The initial workflow is read-only. It will not create or edit Etsy listings.

## API and data notes

- API: Etsy Open API v3
- Current API status: pending personal approval
- Current user count: one
- Public login or signup: none
- Credentials: stored outside this repository
- Scraping: none; the project is intended to use Etsy's API
- Initial write operations: none

I will add the final scopes, resources, and data-retention details after the first working connection is tested. See [PRIVACY.md](PRIVACY.md) for the current data-handling notes.

## Human review

I choose the research topic, review the comparison, write the notes, and approve product decisions. Automation may organize permitted public information, but it does not decide what I sell or publish Etsy listings without my review.

## Boundaries

This project is for market comparison and note-taking. It is not designed to copy listing text, download products, or reproduce another seller's artwork, photos, files, branding, or designs. Product work developed from the research will be created separately as original work.

StarNet Etsy Research is an independent personal project. It is not affiliated with or endorsed by Etsy.

## Contact

Questions about the project can be opened through [GitHub Issues](https://github.com/circlecitygrowth-arch/starnet-etsy-research/issues).
