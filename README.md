inexor-flex-snap
----------------------------

This is the official [snapcraft](https://snapcraft.io) package for `inexor-flex`

## Building
If you're not on linux we recommend using the Docker method as described in the [wiki](https://docs.snapcraft.io/build-snaps/build-on-lxd-docker)

```bash
# from the current directory
docker pull snapcraft/xenial-amd64 # or an alternative architecture. Check out https://hub.docker.com/u/snapcraft/
docker run -v $PWD:$PWD -w $PWD snapcraft/xenial-amd64 snapcraft
```

In the future this snap will be automagically compiled and published to the [uAppExplorer](https://uappexplorer.com) using Launchpad.

## Installing devel-grade snaps
The manually released devel-grade snaps can only be installed in _dangerous_ mode. Run:

```
sudo snap install inexor-flex_0.9.0 --dangerous
```
