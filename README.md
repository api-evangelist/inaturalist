# iNaturalist

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

iNaturalist is a nature observation platform and citizen science network that connects people to nature through biodiversity observation and identification. The platform hosts over 200 million wildlife observations contributed by citizen scientists worldwide, covering taxa identifications, species occurrence records, and biodiversity data.

## API

The iNaturalist API provides programmatic access to observations, species data, identifications, places, projects, and user information. The API is available in three versions:

- **v1** (primary): `https://api.inaturalist.org/v1` — full read/write access
- **v2** (beta): `https://api.inaturalist.org/v2` — next-generation endpoints
- **v0** (legacy): Rails-based, being phased out

### Documentation

- [API Reference](https://www.inaturalist.org/pages/api+reference)
- [API Recommended Practices](https://www.inaturalist.org/pages/api+recommended+practices)
- [Developer Portal](https://www.inaturalist.org/pages/developers)
- [Forum](https://forum.inaturalist.org)

### Authentication

Read access to public data requires no authentication on most endpoints. Write operations and access to private user data require OAuth 2.0 authentication. To obtain credentials, register an application at [https://www.inaturalist.org/oauth/applications/new](https://www.inaturalist.org/oauth/applications/new).

### Key Resources

| Resource | Description |
|---|---|
| Observations | Wildlife sightings with photos, sounds, location, and date |
| Taxa | Species and taxonomic hierarchy data |
| Identifications | Community identifications on observations |
| Places | Geographic areas and administrative boundaries |
| Projects | Curated collections of observations |
| Users | Observer profiles and life lists |
| Controlled Terms | Annotation vocabularies |

### Rate Limits

iNaturalist enforces rate limits to protect service stability. Clients should follow the [API Recommended Practices](https://www.inaturalist.org/pages/api+recommended+practices), including implementing request pacing and caching. For bulk data needs, use the [data export tool](https://www.inaturalist.org/observations/export) or [GBIF](https://www.gbif.org/publisher/28eb1a3f-1c15-4a95-931a-4af90ecb574d) instead of the API.

## Cost

API access is free. iNaturalist is a nonprofit joint initiative of the California Academy of Sciences and the National Geographic Society.

## Links

- [Website](https://www.inaturalist.org)
- [GitHub](https://github.com/inaturalist)
- [Blog](https://www.inaturalist.org/blog)
- [Help](https://help.inaturalist.org)
- [Terms of Service](https://www.inaturalist.org/pages/terms)
- [Privacy Policy](https://www.inaturalist.org/pages/privacy)
