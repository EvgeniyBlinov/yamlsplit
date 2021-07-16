[![MIT License][license-image]][license-url]

# Yamlsplit
Simple python script to split large yaml file by pattern

## Install

```sh
curl -s https://raw.githubusercontent.com/EvgeniyBlinov/yamlsplit/master/yamlsplit -o ~/.local/bin/yamlsplit
chmod +x ~/.local/bin/yamlsplit

```

## Usage

```sh
curl -sL https://github.com/fluxcd/flux2/releases/latest/download/install.yaml | env APP_OUT=./out yamlsplit
```

## License

[![MIT License][license-image]][license-url]

## Author

- [Blinov Evgeniy](mailto:evgeniy_blinov@mail.ru) ([https://evgeniyblinov.ru/](https://evgeniyblinov.ru/))

[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE
