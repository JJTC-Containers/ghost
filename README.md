### Intro
Ghost setup based on Alpine & Node 8 for use with Træfik.

Works with hardened kernel.

This Docker Compose setup is tuned get an A+ grade on https://securityheaders.com/

### Quickstart
To use this you need Docker, Docker Compose & Træfik installed and configured.

Run the following command to get setup:
```
git clone https://github.com/JJTC-Docker/ghost
nano docker-composer.yml
# Replace <YOUR-DOMAIN.TLD> with your domain.
# Replace <YOUR-ACCOUNT> with your https://report-uri.com account (it is free to create one).
```

#### Docker Compose Start/Stop
After the docker-composer.yml file has been modified you can use the default docker-compose commands to start and stop:

```
#  Start as daemon
docker-compose up -d

# Stop
docker-compose down
```