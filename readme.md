# SGCI OOD Image

As an SGCI affiliate we have an [image stored on SGCI's OpenStack host](https://rodeo.tacc.utexas.edu/dashboard/project/instances/) with UTexas.

## Installation

### Follow the general directions

Create an OpenStack instance as described in `howto-setup-on-sgci.pdf` with the following properties:

- Flavor: m1.small
- Instance Name: ood
- Instance Boot Source: Boot from image
- Image Name: CentOS 7

Ensure that there is a security group that permits access on ports 80 and 22.

### Install Open OnDemand and Slurm

Just run `./installer.sh` and it will take care of the rest.