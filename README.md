![1500x500](https://github.com/user-attachments/assets/cd805b9b-1002-4c8c-851c-3026ac91b0c5)

<sub>Banner: One Piece.</sub>

**Hanzalah Waheed** · Founding Engineer at [StockInsights.ai](https://stockinsights.ai) · Dubai, UAE

[Website](https://hanzalahwaheed.com) · [Writing](https://hanzalahwaheed.com/blogs) · [LinkedIn](https://www.linkedin.com/in/hanzalah-waheed-b16456231/) · [X](https://twitter.com/waheed_hanzalah) · [Email](mailto:hanzalah.w@gmail.com)

---

## Work

Founding Engineer at [StockInsights.ai](https://stockinsights.ai) since August 2024.

- Retrieval pipeline over financial filings: `text-embedding-3` and `pgvector` on AWS RDS.
- That pipeline now summarises more than 25,000 filings every month.
- Moved full-text search from MongoDB Atlas to Postgres, with redesigned indexing and relevance scoring.
- Search got about 120% faster and cut over $5,000 a year of infrastructure cost.
- Webhook delivery on SQS and SNS: new filings pushed to customer endpoints.
- That delivery path uses retries and gives consumers at-least-once delivery semantics.
- I also own the frontend, the multi-session chat system, and Stripe metered billing.
- The billing work opened the company's first recurring API revenue stream.

## Writing

I write about Postgres internals, retrieval plumbing, React performance, and open source.

<!-- blogs-start -->

- [Why Updating Data in Postgres Is More Expensive Than You Think](https://hanzalahwaheed.com/blogs/postgres-updates-case-study): MVCC, TOAST, GIN indexes, and when rebuilding beats updating in place.
- [Doomscrolling GitHub, Contributing to OSS and GSoC](https://hanzalahwaheed.com/blogs/oss-and-more): contributing to open source in the age of coding agents.

<!-- blogs-end -->

More at [hanzalahwaheed.com/blogs](https://hanzalahwaheed.com/blogs).

## Open source

Google Summer of Code 2026 contributor at [C2SI](https://github.com/c2siorg), on [DataLoom](https://github.com/c2siorg/dataloom).

- Built the data-profiling engine for DataLoom, an open-source data-wrangling platform.
- Type-aware column statistics, automatic distribution detection, and Pearson correlation heatmaps.
- Widened ingestion and export from CSV only to five formats.
- Added JWT cookie authentication with per-user project ownership at the API layer.
- Wrote over 100 pytest cases across auth, security, and transformations.
- Outside GSoC I contribute to DocsGPT, preCICE, CircuitVerse, and Zulip.
- The table below refreshes itself daily from the GitHub contributions API.

<!-- oss-start -->

| Repository | ⭐ | Merged PRs | Reviews | Issues |
| --- | ---: | ---: | ---: | ---: |
| [c2siorg/dataloom](https://github.com/c2siorg/dataloom) | 25 | 27 | 0 | 33 |
| [arc53/DocsGPT](https://github.com/arc53/DocsGPT) | 18188 | 5 | 0 | 9 |
| [precice/precice.github.io](https://github.com/precice/precice.github.io) | 29 | 2 | 3 | 4 |
| [c2siorg/c2siorg.github.io](https://github.com/c2siorg/c2siorg.github.io) | 3 | 1 | 0 | 2 |
| [CircuitVerse/CircuitVerse](https://github.com/CircuitVerse/CircuitVerse) | 1244 | 1 | 0 | 1 |
| [outerbase/studio-desktop](https://github.com/outerbase/studio-desktop) | 184 | 0 | 0 | 2 |
| [CircuitVerse/CircuitVerseDocs](https://github.com/CircuitVerse/CircuitVerseDocs) | 98 | 1 | 0 | 1 |
| [zulip/zulip](https://github.com/zulip/zulip) | 25591 | 1 | 0 | 0 |
| [outerbase/studio](https://github.com/outerbase/studio) | 5862 | 0 | 0 | 1 |
| [CircuitVerse/cv-frontend-vue](https://github.com/CircuitVerse/cv-frontend-vue) | 61 | 0 | 0 | 1 |

**Totals (all public OSS):** 38 merged PRs · 3 reviews · 63 issues

_Last updated: 2026-08-02_

<!-- oss-end -->
