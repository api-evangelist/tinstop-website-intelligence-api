# Tinstop Website Intelligence API — removed from the API Evangelist network

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
