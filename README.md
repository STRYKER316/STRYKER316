# Hi, I'm Anshil

Backend engineer at Humbee.

I build and run the social-security benefits and insurance distribution
platform behind a 100k+ dealer and distributor network spanning multiple
manufacturers — the machinery that decides who's eligible for what benefit, issues it,
and keeps the record straight as the rules change underneath it.

I own features end to end: the requirements conversation with the business
team, the schema, the API, the migration, the deploy, and the follow-up when a
number looks wrong.

## What I work on

- **Data models that survive a revamp.** Versioned entities, soft deletes that
  mean something, natural keys enforced by a database constraint rather than by
  everyone remembering to check.
- **API boundaries that reject bad data early.** Malformed input fails at the
  edge with a message that still makes sense, not five calls deep where it
  doesn't.
- **Large-scale data movement.** Bulk ingestion tens of thousands of rows at a
  time, and migrations against live tables — where "reject the whole file" and
  "accept it silently wrong" are both failure modes, and the target table is
  never empty.
- **Scheduled jobs that must be safe to re-run.** Idempotency, carry-forward
  rules, and the awkward middle state where the last run stopped halfway.
- **Read paths that stay fast as the table grows.** Don't write N+1 queries,
  index the columns you actually filter on, and cache with a TTL you can reason
  about.

## Tech stack

**Languages**
- Python
- SQL
- Java

**Backend**
- FastAPI
- SQLAlchemy
- Pydantic
- Spring Boot

**Data & messaging**
- PostgreSQL
- Redis
- Kafka
- Elasticsearch
- Alembic

**Infrastructure**
- Docker
- AWS
- Git

## Socials

[LinkedIn](https://www.linkedin.com/in/anshil-mishra/)
