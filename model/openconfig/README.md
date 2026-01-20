# OpenConfig models

This directory contains model packaging for models coming from
the [OpenConfig community](https://github.com/openconfig/public), maintained by members of the OpenConfig community.
These typically start with `openconfig-`.

Since the TransportPCE project must implement data models for transmission equipment of different revisions, the models
at term should exist in different revisions. Device models are packaged per revision, but also across all revisions.

The revisions of models can be bumped across major versions.

YANG files included here should always come from the above OpenConfig github repository.

Model currently packaged are:

- [pre-release 2.0](openconfig-240119)
- [release v2.0.0](openconfig-200)

Although the openconfig models come from the Openconfig GitHub repository, the following adaptations are necessary: 
- use only models necessary for openconfig port-mapping and renderer in TransportPCE project.
- add a common release 2022-06-10 for [pre-release 2.0] and 2026-01-19 for [release v2.0.0] to be able to run
simultaneously both releases.
- add openconfig-platform-common directly inside openconfig-platform.yang models
