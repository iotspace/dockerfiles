dockerfiles [![Build Status](https://travis-ci.org/schickling/dockerfiles.svg)](https://travis-ci.org/schickling/dockerfiles)
===========

Collection of lightweight and ready-to-use docker images

## Images

* **[Beanstalkd](./beanstalkd)** - Lightweight image of the latest beanstalkd version
* **[Beanstalkd-Console](./beanstalkd-console)** - Admin console for Beanstalk queue server
* **[Hugin](./hugin)** - Hugin & Panorama tools
* **[Jekyll](./jekyll)** - Lightweight jekyll working environment
* **[Latex](./latex)** - Full texlive distribution
* **[Mailcatcher](./mailcatcher)** - Extra small mailcatcher image
* **[mysql-backup-s3](./mysql-backup-s3)** - Backup MySQL to S3 (supports periodic backups)
* **[nginx-envtpl](./nginx-envtpl)** - Nginx image with support for environment variables using [envtpl](https://github.com/andreasjansson/envtpl)
* **[NodeJS](./nodejs)** - Minimal NodeJS + NPM image
* **[Octave](./octave)** - Lightweight octave development environment
* **[OpenCV](./opencv)** - Lightweight ready-to use OpenCV image
* **[postgres-backup-s3](./postgres-backup-s3)** - Backup PostgresSQL to S3 (supports periodic backups)
* **[Redis-Commander](./redis-commander)** - Redis management tool
* **[Rust](./rust)** - Lightweight nightly Rust build including Cargo and GDB
* **[swagger-ui](./swagger-ui)** - Swagger UI 2.1.2 with API_URL and API_KEY injection (45 MB)
* **[s3cmd](./s3cmd)** - Lightweight wrapper around s3cmd
* **[thumbor-nginx-cors](./thumbor-nginx-cors)** - Nginx image for thumbor with CORS support

## FAQ

##### Why do you use `install.sh` scripts instead of putting the commands in the `Dockerfile`?

Structuring an image this way keeps it much smaller.
