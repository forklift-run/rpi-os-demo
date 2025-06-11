# rpi-os-demo
Demo OS images with Forklift integration layered over Raspberry Pi OS

## Usage

### Initialization

To make a new repository based on this repository, we recommend that you press the green
"Use this template" button at the top of the GitHub page for this repository. We do NOT recommend
using GitHub's "Fork" button from this repository.

Afterwards, you should update this `README.md` file's Usage and Licensing information accordingly,
and you should update the LICENSE files in this repo accordingly.

### Development

The entrypoint for the OS setup process is [`setup.sh`](./setup.sh). To add more steps to the OS
setup process, add those steps to that file. You can refer to the [`tools` step](./tools/install.sh)
for an example of installing packages with APT. You can refer to the
[`forklift` step](./forklift/install.sh) for an example of copying files from this repo into the OS
image.

## Licensing

We have chosen the following licenses in order to give away our work for free, so that you can
freely use it for whatever purposes you have, with minimal restrictions, while still protecting our
disclaimer that this work is provided without any warranties at all.

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

### Origins

This repository was initialized as a copy of
[github.com/forklift-run/rpi-os-demo](https://github.com/forklift-run/rpi-os-demo). The rpi-os-demo
repository is under copyright of Ethan Li and Forklift project contributors, and it can be used
either under the Apache 2.0 License or under the Blue Oak Model License 1.0.0.

The [github.com/forklift/rpi-os-demo](https://github.com/forklift/rpi-os-demo) repository was
created by Ethan Li as a copy of a subset of original contributions which they had
donated to [github.com/PlanktoScope/PlanktoScope](https://github.com/PlanktoScope/PlanktoScope). The
PlanktoScope repository's source code is licensed under the
[GPL 3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html); because Ethan has retained
copyright ownership over their own individual contributions to the PlanktoScope repository (instead
of assigning copyright to the PlanktoScope project via any legal contract or any
[work-for-hire arrangement](https://worksmadeforhire.com/) with any employer), Ethan has exercised
their legal right to make their own contributions available under additional licenses by gathering
some of their own contributions, copying them into the rpi-os-demo repository, and then making that
source code available under the Apache 2.0 License and under the Blue Oak Model License 1.0.0
(SPDX License Identifier: `Apache-2.0 OR BlueOak-1.0.0`).

### Contributions

Contributions to this repository will only be accepted if the contributor has a legal right to
make the contributed source code available in this repository under this repository's licenses
(which are listed above). In particular, this means that we might not be able to accept a
contribution from you if it includes GPL-licensed source code from
[github.com/PlanktoScope/PlanktoScope](https://github.com/PlanktoScope/PlanktoScope) and you are not
the author of that source code in the PlanktoScope repository, or if you otherwise lack the legal
right (e.g. via copyright ownership) to distribute that source code under this repository's
licenses.
