# connman as a snap

This repo contains code to build connman as snap

# Building the snap

The snap is built with snapcraft. To build the snap:

```bash
git clone
snapcraft
```

# Installing the snap

To install the snap use `--dangerous` for now:

```bash
sudo snap install --dangerous connman*.snap
```

Remember to connect all the required interfaces :)
