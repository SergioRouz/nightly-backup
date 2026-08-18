# nightly-backup

Scheduled encrypted database backups (pg_dump → AES-256 → object storage)
with a monthly restore rehearsal. No application source code lives here —
this repository exists only because GitHub Actions minutes are unlimited
for public repositories.

All credentials are stored as encrypted GitHub Actions secrets.
