# Hi, I'm Anshil

Backend engineer at Humbee.

I build and run the social-security benefits and insurance distribution
platform behind a 100k+ dealer and distributor network spanning multiple
manufacturers — the machinery that decides who's eligible for what benefit,
issues it, and keeps the record straight as the rules change underneath it.

I own features end to end: the requirements conversation with the business
team, the schema, the API, the migration, the deploy, and the follow-ups.

## What I work on

- **Configuration-driven eligibility.** Benefit rules that vary by geography and
  partner role, expressed as configuration rather than code, and resolvable down
  to district level across a national network.
- **Versioned schema design.** Entity versioning, soft-delete semantics, and
  natural keys enforced by partial unique indexes — built to be changed later,
  with live data already sitting in the table.
- **Large-scale data movement.** Bulk ingestion runs of tens of thousands of
  rows, and migrations that move live tables between schema versions while
  reconciling two data formats.
- **Scheduled job pipelines.** Crons that apply those rules each scheme period,
  carry state forward between them, and resume cleanly when a run stops
  halfway.

## Tech stack

**Languages**
- Python
- SQL
- Java

**Backend**
- FastAPI
- SQLAlchemy
- Alembic
- Pydantic
- Spring Boot

**Data & messaging**
- PostgreSQL
- Redis
- Kafka
- Elasticsearch

**Infrastructure**
- Docker
- AWS
- Git

## Socials

[LinkedIn](https://www.linkedin.com/in/anshil-mishra/)
