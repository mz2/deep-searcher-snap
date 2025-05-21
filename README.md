# deep-searcher-snap

deep-searcher packaged as a snap

## Overview

deep-searcher-snap packages the `deep-searcher` tool as a Snap for easy installation and sandboxed execution on Linux systems. This Snap allows you to run `deep-searcher` on any distribution that supports Snap packages.

## Usage

After installation, you can run the CLI tool using:

```sh
deepsearcher load --config-path config.yaml load ...
deepsearcher load --config-path config.yaml query ...
```

## Building the Snap

To build the snap package from source:

```sh
cd snap
snapcraft
```

This will create a `.snap` file in the current directory.

To install the snap from the local directory (for development/testing):

```sh
sudo snap install --dangerous --devmode deep-searcher-snap_*.snap
```

## License

See [LICENSE](LICENSE) for license information (license for the packaging mirrors the upstream project's license).
