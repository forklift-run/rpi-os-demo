# rpi-os-demo
Demo OS images with Forklift integration layered over Raspberry Pi OS

## Usage

The entrypoint for the OS setup process is [`setup.sh`](./setup.sh). To add more steps to the OS
setup process, add those steps to that file. You can refer to the [`tools` step](./tools/install.sh)
for an example of installing packages with APT. You can refer to the
[`forklift` step](./forklift/install.sh) for an example of copying files from this repo into the OS
image.
