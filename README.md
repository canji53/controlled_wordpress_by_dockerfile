# custom_wordpress_by_dockerfile

## About

Customize WordPress environment with Dockerfile.  

## Features

* You can add your own `wp-config.php`.
* Manage `/wp-content/plugins` with dockerfile.
* Locale can be specified where desired. (ex. ja or en, etc...)
* The permission of `/wp-content` has been changed in advance. (ex. chmod 0707 /wp-content)

## Requirement

* Installed Docker

## Usage

```bash
git clone https://github.com/canji53/custom_wordpress_by_dockerfile
cd custom_wordpress_by_dockerfile
docker-compose up -d
```
