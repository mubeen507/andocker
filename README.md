# andocker

This project provides a mechanism to run in a virtualized sandbox the entire Android and React Native ecosystem.
This could be useful for development environment and for testing environment that would have an easy and scalable mechanism to run tests.

To have an explanation on how this tool works please refer to this article: [Android emulation on Docker](https://medium.com/@ccarcaci/android-emulation-on-docker-90d70ea95425)

## Prerequisites

* Docker

## How to Use

Go to the /ecosystem folder, set executable permission to compose.sh script and run it:

```
$ cd ecosystem/
$ chmod +x compose.sh
$ ./compose.sh
```

## License

This project is distributed under [EUPL-1.2](https://eupl.eu/1.2/en).