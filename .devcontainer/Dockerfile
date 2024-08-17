FROM mcr.microsoft.com/devcontainers/rust:1-1-bullseye

RUN apt-get update && apt-get install -y cmake curl clang git pkg-config libssl-dev libdw-dev libpq-dev lld

RUN apt-get install -y postgresql-client

RUN cargo install diesel_cli --no-default-features --features postgres
