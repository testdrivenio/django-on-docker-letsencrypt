# Securing a Containerized Django Application with Let's Encrypt

## Want to learn how to build this?

Check out the [post](https://testdriven.io/blog/django-lets-encrypt/).

## Want to use this project?

### Let's Encrypt Staging

1. Rename *.env.staging-sample* to *.env.staging*, *.env.staging.db-sample* to *.env.staging.db*, and *.env.staging.proxy-companion-sample* to *.env.staging.proxy-companion*. Update the environment variables.
1. Build the images and run the containers:

    ```sh
    $ docker-compose -f docker-compose.staging.yml up -d --build
    ```

    Test it out.

### Let's Encrypt Production

1. Rename *.env.prod-sample* to *.env.prod*, *.env.prod.db-sample* to *.env.prod.db*, and *.env.prod.proxy-companion-sample* to *.env.prod.proxy-companion*. Update the environment variables.
1. Build the images and run the containers:

    ```sh
    $ docker-compose -f docker-compose.prod.yml up -d --build
    ```

    Test it out.
