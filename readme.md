# SMTP TESTER

With SMTP Tester you can easily test if an SMTP server works. You can also send messages with him.

## Use with docker (Without Compose)

Execute the following command:

`docker run --rm -p 80:80 eduardolol/smtp-tester:latest`

Done! Just open your browser with the url of your docker host.

## Example with docker compose

Put into docker-compose.yml

<pre>
version: "3"

services:
  smtpTester:
    image: eduardolol/smtp-tester:latest
    ports:
      - "80:80"
</pre>

## GitHub Repo

## https://github.com/eduardodevop/smtp-tester
