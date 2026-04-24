# Celery (celery)

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
