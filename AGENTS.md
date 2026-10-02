# AccessTrail API — Agent Instructions

## Project Purpose

AccessTrail API is a learning and portfolio project.

It models a common IT access-provisioning control:

request access -> approve/reject -> grant access -> audit trail

The project is intended to help me:

- improve my backend engineering skills
- learn PostgreSQL and relational database design
- practise NestJS architecture
- understand access-control and audit concepts relevant to IT risk/GRC
- build a portfolio project I can explain confidently in interviews

## Tech Stack

- NestJS
- TypeScript
- PostgreSQL
- TypeORM
- Docker
- Jest
- GitHub Actions

## How to Work With Me

I am learning. Do not build the project for me.

Before making changes:

1. Explain what we are about to do.
2. Explain why we need it.
3. Give me a chance to understand or ask questions.

Prefer hints and guidance over complete solutions.

If I explicitly say "write it", you may provide or implement the full solution.

Keep changes small and focused. Do not implement multiple features at once.

## Code Changes

- Prefer small diffs.
- Do not perform unrelated refactors.
- Do not implement future features early.
- Explain unfamiliar NestJS, TypeORM, PostgreSQL, or TypeScript concepts.
- When there are multiple reasonable approaches, explain the trade-offs before choosing one.
- Do not add dependencies without asking me first.

## Testing

Prefer tests before implementation when adding behaviour.

Explain:

- what the test is checking
- why the test matters
- what behaviour should make it pass

Do not simply modify tests to make failing code pass.

## Security and Secrets

Never read, display, modify, or expose:

- `.env` files
- API keys
- passwords
- access tokens
- private keys
- credentials
- other secrets

For authentication, JWTs, password storage, password hashing, authorization,
or other security-sensitive implementation:

1. Explain the security concept first.
2. Point me to the relevant official NestJS documentation and/or OWASP guidance.
3. Do not implement it until I approve.

## Git

Do not commit, push, merge, rebase, or modify Git history unless I explicitly ask.

Before a commit, explain what will be included in it.

## Scope

Current MVP:

- tenants
- users
- roles: admin, approver, requester
- access request workflow
- approve/reject workflow
- access grant
- status history
- append-only audit log recording who, what, and when
- CSV audit-log export
- tests
- Docker
- CI with GitHub Actions

Do not implement features outside the current task just because they appear in the MVP.
