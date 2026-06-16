# OpenConfig models

This directory contains model packaging for models coming from
the [OpenConfig community](https://github.com/openconfig/public), maintained by members of the OpenConfig community.
These typically start with `openconfig-`.

Since the TransportPCE project must implement data models for transmission equipment of different revisions, the models
at term should exist in different revisions. Device models are packaged per revision, but also across all revisions.

The revisions of models can be bumped across major versions.

YANG files included here should always come from the above OpenConfig github repository.

Model currently packaged are:

- [release v2.0.0](openconfig-200)
- [release v5.6.0](openconfig-platform-5.6.0, openconfig-terminal-devices-5.6.0, openconfig-system-5.6.0)

release recently removed:
- [pre-release 2.0](openconfig-240119)