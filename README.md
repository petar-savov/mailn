Email newsletter API from [Zero to Production in Rust](https://www.zero2prod.com/). Includes an async REST API, subscriber management, retry-safe content delivery, authentication and logging. Uses

- [Actix Web](https://actix.rs/)
- [SQLx](https://github.com/launchbadge/sqlx)
- [Tracing](https://docs.rs/tracing/latest/tracing/)
- PostgreSQL
- Redis

---

To launch a database locally using Docker:

> ./scripts/init_db.sh

To launch a Redis container locally:

> ./scripts/init_redis.sh

Run with

> cargo run

Run all tests with

> cargo test

Demo username/password for /login
> admin / everythinghastostartsomewhere
