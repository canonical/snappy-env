# Snappy Env

This program can be used to add runtime environment variable support to snaps. 
By adding this program to the command chain of snapped applications, it will add support for:
- Converting snap options to environment variables based on a custom mapping
- Taking path to env files as input, loaded before starting the applications

The program is intended to be used by the Env Injector Snapcraft extension; the documentation for that is available [here](https://snapcraft.io/docs/env-injector).

There are currently two implementations for the Snapcraft extension. The Rust implementation is considered more stable.

To use snappy-env directly and without the Snapcraft extension; refer to [snap/snapcraft.yaml](snap/snapcraft.yaml) as an example.
