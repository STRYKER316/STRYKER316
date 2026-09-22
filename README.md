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

## Opinions I'll defend

- Invalid data gets rejected at the API boundary, not five calls deep where the
  error message has stopped making sense.
- A migration must never assume its target table is empty.
- The transaction boundary lives in exactly one layer; everything below it
  flushes, nothing below it commits.
- Design docs before the code, and updated with it — most of a feature's cost is
  the second person reading it.

## Selected work

**[event-ticketing-platform](https://github.com/STRYKER316/event-ticketing-platform)**
— reserved-seat booking platform, five event-driven microservices over Kafka.
Two seat-hold concurrency strategies (Postgres sweep vs. Redis TTL lock)
benchmarked head-to-head under concurrent load, Stripe payments with idempotent
webhook handling, Keycloak OIDC, Elasticsearch search. MS CS capstone.

## Stack

Python · FastAPI · SQLAlchemy · PostgreSQL · Redis · Kafka · Docker · AWS
Earlier: Java, Spring Boot

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/anshil-mishra/)
