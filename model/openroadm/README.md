# OpenROADM models

This directory contains model packaging for models coming from
the [OpenROADM community](https://github.com/OpenROADM/OpenROADM_MSA_Public), maintained by OpenROADM community. These
typically start with `org-openroadm-`.

Note, however, that we sometimes find models from the openconfig community among openroadm models (device-7.1.0,
device-13.1.0 as an example), when OpenROADM imports already existing data models (no need to reinvent the wheel).

Since the TransportPCE project must implement data models for transmission equipment of different revisions, the models
in the common and device directories exist in different revisions. Device models are packaged per revision, but also
across all revisions.

The revisions of models can be bumped across major versions.

YANG files included here should always come from the above OpenROADM github repository.

Model currently packaged are:

- [common for 1.2.1 revision](common-1.2.1)
- [common for 2.2.1 revision](common-2.2.1)
- [common for 7.1.0 revision](common-7.1.0)
- [common for 13.1.1 revision](common-13.1.1)
- [device for 1.2.1 revision](device-1.2.1)
- [device for 2.2.1 revision](device-2.2.1)
- [device for 7.1.0 revision](device-7.1.0)
- [device for 13.1.1 revision](device-13.1.1)
- [network for 13.1.1 revision](network-13.1.1)
- [service for 13.1.1 revision](service-13.1.1)