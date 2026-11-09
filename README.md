# Protected application scheduler

This repository contains only a small scheduled workflow for invoking protected maintenance endpoints of a personal application.

It contains no application source, credentials, personal records, response bodies, or activity statistics. The workflow does not check out or execute pull requests. Its application credential is stored only as a GitHub Actions secret.

The normal schedule runs twice an hour. A separate monthly maintenance job updates this document using the short-lived, repository-scoped GitHub token. Workflow logs contain HTTP statuses only.

Last maintenance: initial setup.
