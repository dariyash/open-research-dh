# Open Heritage Data, Source Catalogue

A vetted starting list of open cultural-heritage sources, with **access type**, formats, and licence.
Use it for the Module 2 explore task and for finding data for your own project.

*Access legend:* **DL** = direct download (CSV/JSON/ZIP) · **API** = open API, no key ·
**API-key** = free key required · **token** = free account/token required · **preview** = view-only.

> **Links last verified: 16 September 2026.** Every link below resolves. Notes marked flag a
> licence/access detail that is easy to get wrong; notes marked flag something that changed
> recently. Where a metadata licence differs from the image/object licence, both are given.

## Already on the course radar
| Source | Link | Access | Licence |
|---|---|---|---|
| MET Museum | metmuseum.org/hubs/open-access | DL + API | CC0 (metadata) |
| Smithsonian | si.edu/openaccess | DL + API-key | CC0 |
| Rijksmuseum | data.rijksmuseum.nl | API (no key) + DL | CC-BY metadata; most images PD |
| Europeana | europeana.eu / pro.europeana.eu | API-key + DL | aggregated; varies |
| European Data | data.europa.eu | portal + API + DL | varies |

- **Rijksmuseum** The platform has been rebuilt around **Linked Open Data**: the new Search API
 needs **no key**, and there's OAI-PMH plus a **full bulk download**. The old keyed API is
 deprecated. Metadata is **CC-BY** (attribute "Rijksmuseum Amsterdam"); digitised works are
 largely public domain.
- **Europeana** Since 28 May 2025 the free API key is requested through a **Europeana account**
 (the old standalone form is gone). Content is aggregated, so licences vary item by item.

## More museum & collection open data
| Source | Link | Access | Licence |
|---|---|---|---|
| Art Institute of Chicago | artic.edu/open-access | API + DL (GitHub) | CC0 ( `description` field is CC-BY) |
| Cleveland Museum of Art | openaccess-api.clevelandart.org | API + DL | CC0 |
| Harvard Art Museums | github.com/harvardartmuseums/api-docs | API-key | reusable, but restrictive terms |
| Museum of Modern Art (MoMA) | github.com/MuseumofModernArt/collection | DL (CSV/JSON) + API | CC0 |
| Cooper Hewitt (Smithsonian) | github.com/cooperhewitt/collection | DL + API-token | CC0 |
| Tate | github.com/tategallery/collection | DL | CC0 ( not updated since Oct 2014) |
| National Gallery of Art (US) | github.com/NationalGalleryOfArt/opendata | DL (CSV) | CC0 |
| Victoria & Albert Museum | developers.vam.ac.uk | API | V&A terms, not CC0 |
| Paris Musées | parismuseescollections.paris.fr | portal + API-token | CC0 (open images) |

- **Harvard Art Museums** The API key is free (register via form), but the terms are restrictive:
 attribution and link-back required, no caching content for more than two weeks, ~2,500 calls/day.
 Not an open licence, treat as "reusable under conditions."
- **MoMA** Now also offers an official API at **api.moma.org** in addition to the CSV/JSON dump.
- **Cooper Hewitt** The `collection` GitHub repo is a static/older release; the live API
 (apidocs.cooperhewitt.org) needs a free access token.
- **V&A** The v2 API (api.vam.ac.uk/v2) queries without a key, but images and metadata fall under
 the **V&A's own terms & conditions**, not CC0; commercial image use requires a licence.
- **Paris Musées** The API needs a free account/token (apicollections.parismusees.paris.fr).
 parismusees.paris.fr is the parent institutional site; the data lives at the collections portal above.

## Libraries, archives & aggregators
| Source | Link | Access | Licence |
|---|---|---|---|
| Digital Public Library of America | dp.la (dev docs: pro.dp.la) | API-key + DL | aggregated; varies |
| Library of Congress | loc.gov/apis · data.labs.loc.gov | API + DL | mostly public domain |
| Trove (Nat. Library of Australia) | trove.nla.gov.au | API-key | aggregated; varies |
| Finna (Finnish GLAM) | api.finna.fi | API | metadata CC0; items vary |

- **Library of Congress** A new catalog platform launched 30 June 2025; the loc.gov JSON API data
 is being restored/re-synced incrementally, so some records may be temporarily incomplete. No key required.
- **Trove** Now on **API v3** (v2 deprecated). In early 2025 the NLA tightened enforcement: the API
 is **metadata-only** and bulk full-text extraction now violates the Terms of Use. Still free (key required),
 just more restrictive than before.

## German / NFDI infrastructure (for the own-project path)
| Source | Link | Notes |
|---|---|---|
| NFDI4Culture | nfdi4culture.de | material & immaterial cultural heritage (Culture Knowledge Graph + SPARQL endpoint) |
| NFDI4Objects | nfdi4objects.net | archaeology & material culture |
| NFDI4Memory | 4memory.de | historically working disciplines |

## Authority / reference data (for Module 6 enrichment, not primary collections)
| Source | Link | Access | Licence |
|---|---|---|---|
| Wikidata | query.wikidata.org | SPARQL + API | CC0 |
| Getty Vocabularies (AAT/ULAN/TGN) | getty.edu/research/tools/vocabularies | LOD + DL | ODC-BY |

- **Wikidata** query.wikidata.org is live (SPARQL at query.wikidata.org/sparql, plus REST and
 Action APIs; all CC0). Note the 2025 WDQS **graph split**: query.wikidata.org now serves only the
 **main graph**, scholarly-article items moved to a separate endpoint (query-scholarly.wikidata.org).
 Fine for GLAM enrichment (people, places, works); only matters if a query touches scholarly articles.
- **Getty** As of ~January 2026 Getty discontinued the XML and relational-table downloads. Data is now
 served as Linked Open Data (JSON/RDF/Turtle/N-Triples) via the SPARQL endpoint and download center,
 refreshed monthly. CONA and IA are web-service only.

## Ready-made CSVs on Kaggle (zero setup; mirrors of official data)
| Dataset | Link |
|---|---|
| The Met Open Access | kaggle.com/datasets/metmuseum/the-metropolitan-museum-of-art-open-access |
| MoMA Collection | kaggle.com/datasets/momanyc/museum-collection |
| National Gallery of Art Open Data | kaggle.com/datasets/peacehegemony/the-national-gallery-of-art-open-data-program |
| WikiArt (120k+) | kaggle.com/datasets/antoinegruson/-wikiart-all-images-120k-link |

- The **WikiArt** set is the odd one out: it's a table of scraped image **links** (not the images), and
 it is **not CC0**, WikiArt's underlying content licensing varies. The MoMA (2017) and WikiArt (2021)
 mirrors are several years old; the Met and NGA mirrors track the official data more closely.

## Find your own
- Google Dataset Search, datasetsearch.research.google.com
- GLAM Workbench, glam-workbench.github.io

> Tip: several Kaggle sets mirror the official museum data, convenient for class, but cite the
> authoritative, current version at the source institution. This matters most for the older mirrors
> (MoMA, WikiArt) and for anything you plan to publish.
