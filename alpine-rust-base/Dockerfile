FROM alpine:3.7
LABEL org.label-schema.name="docker-alpine-rust" \
      org.label-schema.description="Docker Alpine Rust Cargo" \
      org.label-schema.url="https://hub.docker.com/r/sitkevij/alpine-rust/" \
      org.label-schema.usage="https://github.com/sitkevij/alpine-rust/blob/master/README.md" \
      org.label-schema.vcs-url="https://github.com/sitkevij/alpine-rust" \
      org.label-schema.vendor="sitkevij" \
      org.label-schema.version="0.1.0" \
      maintainer="https://github.com/sitkevij"
RUN cd && \
apk update && \
apk upgrade && \
apk add rust cargo
# sitkevij/alpine-rust 263 MB in 35 packages, compressed: 111 MB
# Linux 4e2d0e23b7ff 4.9.60-linuxkit-aufs #1 SMP Mon Nov 6 16:00:12 UTC 2017 x86_64 Linux