### Vishwajeet Deshmukh

Backend engineer at Jio Platforms in Navi Mumbai. I've written Go in production for three years.

Most of my work is on JioCX, Jio's RCS messaging platform. It handles millions of messages a day on GCP and Kubernetes, and my part is the Go services, the databases behind them, and the Kafka pipelines between them. I cut API response times by 30% there by tuning MySQL queries, caching in Redis, and moving the heaviest workloads to ScyllaDB. Lately I've been building LLM-based checks that screen RCS templates for spam and policy problems.

#### Things here worth opening

- [Booking-System](https://github.com/MrVishwajeetDeshmukh/Booking-System): a seat reservation API in Go and PostgreSQL. It places temporary seat holds, makes requests idempotent, issues signed tokens, and exposes Prometheus metrics. It runs on Render.
- [task-management-api](https://github.com/MrVishwajeetDeshmukh/task-management-api): a task API built with Fiber, using JWT auth, role-based access, and background workers that complete tasks automatically.
- [pdfPasswordRemover](https://github.com/MrVishwajeetDeshmukh/pdfPasswordRemover): a small Fiber service that removes the password from a PDF entirely in memory. There's a [live version](https://pdf-password-remover-orpin.vercel.app).
- [my-interactive-portfolio](https://github.com/MrVishwajeetDeshmukh/my-interactive-portfolio): my website, which includes a live simulation of a Kafka consumer group.

#### What I use

Go (Fiber, Gin, net/http), PostgreSQL, MySQL, ScyllaDB, Redis, Apache Kafka, Docker, Kubernetes (GKE), GCP, Azure.

#### Elsewhere

[vishwajeetd.com](https://vishwajeetd.com) · [LinkedIn](https://www.linkedin.com/in/vishwajeetd/) · deshmukhv.vishwajeet@gmail.com
