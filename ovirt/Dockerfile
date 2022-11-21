FROM quay.io/kubev2v/fakeovirt:latest

WORKDIR /app

COPY stubs stubs
# COPY certs/server.crt .
# COPY certs/server.key .

ENV PORT=30001
EXPOSE 30001
