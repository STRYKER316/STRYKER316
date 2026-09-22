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
- **Bulk ingestion.** Tens of thousands of rows per run, where "reject the whole
  file" and "accept it silently wrong" are both failure modes.
- **Scheduled jobs that must be safe to re-run.** Idempotency, carry-forward
  rules, and the awkward middle state where the last run stopped halfway.
- **Read paths that stay fast as the table grows.** Mostly: don't write N+1
  queries, and index the columns you actually filter on.
- **Migrations against live data**, which never assume the target table is
  empty.

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

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/anshil-mishra/)
