# Garden Linux Build Scripts

## build system recommendations (per concurrent build)

- 2+ GiB (use RAM-disk; use fs with sparse-file support)
- 10+ GiB free disk space

## Documentation

Install required packages using apt:

    apt install docker.io make

Install recommended packages for better build performance and tests in a virtualizer

    apt install docker-compose qemu-system-x86

Build all images:

    make all

Build specific images:

    make aws
    make gcp
    make azure
    make vmware
    make openstack
    make vmware
    make kvm

## License

Copyright 2020 by SAP SE
