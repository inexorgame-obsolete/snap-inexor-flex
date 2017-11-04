inexor-flex-snap
----------------------------

This is the official [snapcraft](https://snapcraft.io) package for `inexor-flex`

## Building
If you're not on linux we recommend using the Docker method as described in the [wiki](https://docs.snapcraft.io/build-snaps/build-on-lxd-docker)

```bash
# from the current directory
docker pull snapcore/snapcraft
docker run -v $PWD:$PWD -w $PWD snapcore/snapcraft snapcraft
```

This snap is automagically compiled and published to the [uAppExplorer](https://uappexplorer.com) using Launchpad.
