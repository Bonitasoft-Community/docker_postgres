This image is based on Postgres [9.3](https://github.com/docker-library/postgres/blob/8f80834e934b7deaccabb7bf81876190d72800f8/9.3/Dockerfile) from the [PostgreSQL Official Repo](https://registry.hub.docker.com/_/postgres/).

The only differences are that we set max_prepared_transactions to 100 and accept remote connections from all users.
