# Sneaky Backlinks Playbook

Weekly process for discovering and cataloging high-DR profile, Web 2.0, directory, UGC, and parasite SEO opportunities.

## Goal
Systematically find high Domain Rating (DR 70+) sites that allow free or low-friction backlinks (profiles, listings, publishing, UGC) to build a foundation of link equity and support parasite SEO campaigns.

## Core Principles (from Connor Showler and research)
- **Parasite SEO**: Publish content on high-authority platforms (Reddit, Quora, Medium, LinkedIn, Substack, Ghost, etc.) to hijack their rankings for long-tail keywords and get cited by AI Overviews / LLMs.
- **Volume foundation**: Build a large set of free profile / directory / Web 2.0 links as a base.
- **Agency mining**: Use Ahrefs / SEMrush to reverse-engineer backlink profiles of top SEO agencies and their clients for exotic high-DR opportunities.
- **Uniqueness**: Always check the MongoDB collection before inserting.
- **Verification**: Prefer live DR, link type (dofollow/mixed/nofollow), and indexing status over list claims.

## Weekly Process
1. Review new posts from key accounts (e.g. @ConnorShowler).
2. Mine SEO agency + client backlink profiles.
3. Run search operators for directories, Web 2.0, and publishing platforms.
4. Check candidates against `sneaky_backlinks.opportunities`.
5. Insert unique high-DR ones with full schema.
6. Update null DR values on existing high-value entries.
7. Document new techniques or platforms.

## Collection
- Database: `sneaky_backlinks`
- Collection: `opportunities`
- Connection ID: `a108f6b1-5865-47b9-b171-4f14e1222f00`

## Categories
- Profile / Social
- Web 2.0 / Publishing
- Directory / Listing
- Document / Presentation
- Image / Video
- Academic / Professional
- Link-in-bio
- Event / Service
- Software / Package

See other files for detailed strategies, search techniques, and schema.
