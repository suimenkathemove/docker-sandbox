FROM rust:1.65.0

WORKDIR /usr/src/rust-app
COPY . .

RUN cargo install --path .

CMD ["rust-app"]
