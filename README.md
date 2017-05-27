# Extended PHP 7.0 / Apache 

This image is extended to meet Laravel requirements.

## Getting Started

1. Pull image ```docker pull aleksxp/php7.0-apache-extended```
1. Run ```docker run -d --name some-php -p 8080:80 -v $(pwd)/src:/var/www/html aleksxp/php7.0-apache-extended```

Read more about **docker run** option in [official Docker documentstion](https://docs.docker.com/engine/reference/run/).

### Prerequisites

1. [Docker](https://docs.docker.com/engine/installation/)


## Authors

* **Alexander Pankov** <ap@wdevs.ru>

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details