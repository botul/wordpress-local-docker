[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/botul){:target="_blank"}

# wordpress-local-docker
### Docker compose setup for local Wordpress development.

## Contents:
* A naginx Dockerfile for extending a base image and setup the ssl certs 
* PHP 8.1
* Custom local domain and HTTPS support
* Custom nginx config in ./nginx
* Custom php.ini options
* Volumes for nginx and mysql

## Setup

Copy .env.example in the project root to .env and edit your preferences.

```bash 
CONTAINER_NAME=wp1
HOSTNAME=wp1.a.local
DATABASE_NAME=wp1_db
DATABASE_USER=wp1_dbusr
DATABASE_PASSWORD=YourPasswordForDBUser
DATABASE_ROOT_PASSWORD=RootDBUserPassword
```