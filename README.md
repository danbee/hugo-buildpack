# Hugo Buildpack
This is a naive CNCF buildpack for hugo websites. This can allow hugo projects to be hosted on cloud foundry, heroku, and spaceship.

## Build a project w/ pack

```
pack build myproject -p . -b ../hugo-buildpack
```

## Run the built image

```
docker run --rm -ePORT=3000 -p3000:3000 myproject
```

## Environment Setup

```
brew install pack
```

## Contributing
PRs welcome. If you need help or want to reach out email is best patrick.wiseman@spaceship.run

## Contributors
[Patrick Wiseman](mailto:patrick.wiseman@spaceship.run)

## License
[Apache 2.0 License](./LICENSE)

## Acknowledgements

## Checkout
[CNCF Buildpacks](https://buildpacks.io)
[Spaceship](https://spaceship.run)
