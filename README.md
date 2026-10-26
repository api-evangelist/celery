# Celery (celery)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Celery is an open-source distributed task queue for Python. This repository captures the APIs, developer tools, and machine-readable API artifacts for Celery.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/celery/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** Open Source

## Tags

- Asynchronous
- Distributed Systems
- Message Queue
- Open Source
- Python
- Task Queue

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-23

## APIs

### Celery Task API

Core API for defining and executing distributed tasks in Celery. Supports task decorators, retries, timeouts, rate limiting, and custom task classes.

**Human URL:** [https://docs.celeryq.dev/en/stable/userguide/tasks.html](https://docs.celeryq.dev/en/stable/userguide/tasks.html)

#### Tags

- Python, Task Queue, Tasks

#### Properties

- [Documentation](https://docs.celeryq.dev/en/stable/userguide/tasks.html)
- [Reference](https://docs.celeryq.dev/en/stable/reference/celery.app.task.html)
- [GettingStarted](https://docs.celeryq.dev/en/stable/getting-started/)

### Celery Application API

Application configuration and initialization API for Celery, used to configure brokers, result backends, serialization, routing, and task discovery.

**Human URL:** [https://docs.celeryq.dev/en/stable/userguide/application.html](https://docs.celeryq.dev/en/stable/userguide/application.html)

#### Tags

- Application, Configuration

#### Properties

- [Documentation](https://docs.celeryq.dev/en/stable/userguide/application.html)
- [Reference](https://docs.celeryq.dev/en/stable/reference/celery.html)
- [Configuration](https://docs.celeryq.dev/en/stable/userguide/configuration.html)

### Celery Canvas API

Canvas is Celery's workflow composition API for building complex task orchestrations using signatures, chains, groups, chords, maps, starmaps, and chunks.

**Human URL:** [https://docs.celeryq.dev/en/stable/userguide/canvas.html](https://docs.celeryq.dev/en/stable/userguide/canvas.html)

#### Tags

- Workflows, Chains, Groups, Chords

#### Properties

- [Documentation](https://docs.celeryq.dev/en/stable/userguide/canvas.html)

### Celery Beat API

Celery Beat is the scheduler for periodic tasks, supporting crontab-style schedules, interval schedules, and solar schedules. It can also be backed by a database scheduler for dynamic schedules.

**Human URL:** [https://docs.celeryq.dev/en/stable/userguide/periodic-tasks.html](https://docs.celeryq.dev/en/stable/userguide/periodic-tasks.html)

#### Tags

- Scheduling, Periodic Tasks

#### Properties

- [Documentation](https://docs.celeryq.dev/en/stable/userguide/periodic-tasks.html)
- [Reference](https://docs.celeryq.dev/en/stable/reference/celery.beat.html)

### Celery Worker API

Worker API for executing distributed tasks with configurable concurrency (prefork, gevent, eventlet, solo, threads), autoscaling, remote control, and signal handling.

**Human URL:** [https://docs.celeryq.dev/en/stable/userguide/workers.html](https://docs.celeryq.dev/en/stable/userguide/workers.html)

#### Tags

- Worker, Execution, Concurrency

#### Properties

- [Documentation](https://docs.celeryq.dev/en/stable/userguide/workers.html)
- [Reference](https://docs.celeryq.dev/en/stable/reference/celery.worker.html)

### Celery Result Backend API

Result backend API for storing and retrieving task results and state using backends such as Redis, RPC, database, Memcached, Cassandra, and S3.

**Human URL:** [https://docs.celeryq.dev/en/stable/userguide/tasks.html#result-backends](https://docs.celeryq.dev/en/stable/userguide/tasks.html#result-backends)

#### Tags

- Results, State, Storage

#### Properties

- [Documentation](https://docs.celeryq.dev/en/stable/userguide/tasks.html#result-backends)
- [Reference](https://docs.celeryq.dev/en/stable/reference/celery.result.html)

### Celery Signals API

Signals API for hooking into Celery lifecycle events including task, worker, beat, and consumer signals to build extensions and observability.

**Human URL:** [https://docs.celeryq.dev/en/stable/userguide/signals.html](https://docs.celeryq.dev/en/stable/userguide/signals.html)

#### Tags

- Signals, Events, Extensions

#### Properties

- [Documentation](https://docs.celeryq.dev/en/stable/userguide/signals.html)
- [Reference](https://docs.celeryq.dev/en/stable/reference/celery.signals.html)

### Celery Monitoring and Events API

Event streaming and monitoring API for inspecting workers, tasks, and queues. Supports the curses-based celery events monitor and third-party tools such as Flower.

**Human URL:** [https://docs.celeryq.dev/en/stable/userguide/monitoring.html](https://docs.celeryq.dev/en/stable/userguide/monitoring.html)

#### Tags

- Monitoring, Events, Observability

#### Properties

- [Documentation](https://docs.celeryq.dev/en/stable/userguide/monitoring.html)
- [Reference](https://docs.celeryq.dev/en/stable/reference/celery.events.html)

## Common Properties

- [Website](https://docs.celeryq.dev/)
- [Documentation](https://docs.celeryq.dev/en/stable/)
- [Reference](https://docs.celeryq.dev/en/stable/reference/index.html)
- [GettingStarted](https://docs.celeryq.dev/en/stable/getting-started/)
- [GitHub](https://github.com/celery/celery)
- [PyPI](https://pypi.org/project/celery/)
- [ChangeLog](https://docs.celeryq.dev/en/stable/changelog.html)
- [Community](https://github.com/celery/celery/discussions)
- [Issues](https://github.com/celery/celery/issues)
- [Contributing](https://docs.celeryq.dev/en/stable/contributing.html)
- [License](https://github.com/celery/celery/blob/main/LICENSE)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
