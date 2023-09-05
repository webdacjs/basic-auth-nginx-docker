# Basic auth in nginx with docker

This repo contains a simple example that serves a "Hello World" page using the base nginx docker image. The path is protected by basic auth using `test` and `test` as username and password.

The basic structure is:

```

├── docker-compose.yml
├── log
├── nginx.conf
└── static
    └── index.html

```

In order to run it, please clone this repo, execute `docker compose up` and should have the server running on port 80.

*Note*: The test / test .htpasswd is checked-in in this test template. You shouldn't that on a real app of course :)
