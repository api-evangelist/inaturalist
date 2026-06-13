# iNaturalist

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
