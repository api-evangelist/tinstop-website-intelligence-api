# Tinstop Website Intelligence API — removed from the API Evangelist network

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

This profile was **removed on 2026-08-11** as catalog hygiene. It was not an
owner request; nobody asked us to take it down. We removed it because the
service is gone.

## Why

`tinstop.com` is a parked domain listed for sale on GoDaddy's aftermarket. The
site's own `/llms.txt` states it plainly:

> tinstop.com is a domain name currently listed for sale on GoDaddy's aftermarket.

Every path on the domain returns `HTTP 200` with an HTML redirect to `/lander`,
including nonsense paths, so a status code alone reads as healthy when nothing
is there. `/openapi.json` serves that lander page rather than a specification.
Earlier probes on 2026-08-02 and 2026-08-04 found a TLS handshake failure and
Cloudflare error 1001 — an origin DNS failure — so the host had already been
unreachable for over a week.

## This listing should not have existed

The submission was auto-published by the apis.io Add-API form on 2026-07-19.
The same request was declined by hand, twice, on the submitter's GitHub issue
— on 2026-08-02 and again on 2026-08-04 — because the domain would not resolve.
The automated path and the human path disagreed and the automated one won. That
gap is tracked at https://github.com/api-evangelist/roadmap/issues/20.

## What was published, and what was not

Nothing was fabricated. This repository never held an OpenAPI or any harvested
artifact, because there was never a reachable host to harvest from — only an
`apis.yml` built from the submission text. It was nonetheless re-scored 22
times between 2026-07-27 and 2026-08-10 against a host that did not answer, and
carried a published Kin Score of 14.0 (emerging) until removal. That score is
deleted rather than zeroed: it measured our inability to reach a dead domain,
not anything about a business.

## Status

The company is on the API Evangelist delisting registry, so no harvest,
enrichment or submission can re-publish it. If you have acquired `tinstop.com`
and want a listing, that is a new submission about your service, not this one:
**kin@apievangelist.com**.
