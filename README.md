# Snappy Env

This program can be used to add runtime environment variable support to snaps. 
By adding this program to the command chain of snapped applications, it will add support for:
- Converting snap options to environment variables based on a custom mapping
- Taking path to env files as input, loaded before starting the applications

The program is intended to be used by the Env Injector extension; the documentation for that is available [here](https://forum.snapcraft.io/t/the-env-injector-extension/41477).

There are currently two implementations for the extension. The Rust implementation is considered more stable.

The program can also be used without the extension. Refer to [snap/snapcraft.yaml](snap/snapcraft.yaml) for an example.

Testing and benchmarking scripts are under [tests](/tests).
