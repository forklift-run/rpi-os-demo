# rpi-os-demo
Demo OS images with Forklift integration layered over Raspberry Pi OS

## Usage

The entrypoint for the OS setup process is [`setup.sh`](./setup.sh). To add more steps to the OS
setup process, add those steps to that file. You can refer to the [`tools` step](./tools/install.sh)
for an example of installing packages with APT. You can refer to the
[`forklift` step](./forklift/install.sh) for an example of copying files from this repo into the OS
image.

## Licensing

We have chosen the following licenses in order to give away our work for free, so that you can
freely use it for whatever purposes you have, with minimal restrictions, while still protecting our
disclaimer that this work is provided without any warranties at all. If you're using this project,
or if you have questions about the licenses, we'd love to hear from you - please start a new
discussion thread in the "Discussions" tab of this repository on Github or email us at
<lietk12@gmail.com> .

### Software

Except where otherwise indicated, source code provided here is covered by the following information:

**Copyright Ethan Li and Forklift project contributors**

SPDX-License-Identifier: `Apache-2.0 OR BlueOak-1.0.0`

Software files in this repository are released under the
[Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0) and the
[Blue Oak Model License 1.0.0](https://blueoakcouncil.org/license/1.0.0);
you can use the source code provided here either under the Apache License or under the
Blue Oak Model License, and you get to decide which license you will agree to.
We are making the software available under the Apache license because it's
[OSI-approved](https://writing.kemitchell.com/2019/05/05/Rely-on-OSI.html),
but we like the Blue Oak Model License more because it's easier to read and understand.
Please read and understand the licenses for the specific language governing permissions and
limitations.
