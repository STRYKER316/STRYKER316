# Anshil Mishra

Backend engineer. I work on benefit and insurance distribution systems — the
machinery that decides who's eligible for what, issues it, and keeps the record
straight a year later when the rules have changed twice.

Currently at Humbee. I own features end to end: the requirements conversation
with the business team, the schema, the API, the migration, the deploy, and the
follow-up when a number looks wrong.

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

## Stack

Python · FastAPI · SQLAlchemy · PostgreSQL · Redis · Kafka · Docker · AWS
Earlier: Java, Spring Boot

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/anshil-mishra/)
