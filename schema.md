# MongoDB Schema

Collection: `sneaky_backlinks.opportunities`

| Field | Type | Description |
|-------|------|-------------|
| name | string | Platform name |
| website_url | string | Homepage or signup URL |
| category | string | profile, web2.0, directory, document, image, video, academic, etc. |
| domain_rating | number | Ahrefs DR (or null) |
| domain_authority | number | Moz DA (or null) |
| outbound_link_rel | string | dofollow / nofollow / mixed / unverified |
| notes | string | How to get the link, caveats, source |
| verification_status | string | discovered / pending / verified |
| research_date | string | YYYY-MM-DD |
| source | string | e.g. ConnorShowler X, agency mining, search operator |
| instructions | string | Optional step-by-step |
| source_urls | array | Optional supporting links |

## Insert rules
1. Always check for existing name or website_url first.
2. Prefer inserting with as many fields filled as possible.
3. Update null DR values when new data is found.
4. Avoid concurrent insert-many calls; coordinate with the team.
