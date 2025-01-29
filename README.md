# Dummy Ignition

Simple Ignition file for use with Fedora CoreOS, that gives the `core` user the `fedora` password.

## Example

When installing via the FCOS ISO:

```bash
sudo coreos-installer install /dev/DISK --ignition-url https://tinyurl.com/dummy-fcos-ign
```

## Template

You can use this project as a template. Just edit `config.bu`.
