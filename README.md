# SAP HANA Express instrumented with AppDynamics using Docker

The intent behind this repository is to provide a local testing environment of SAP HANA Express built with Docker, running on an Ubuntu Machine.

## Machine Requirements

- Ubuntu 18.04
- t2.xlarge (4x16)

### Ports for Security Group

- 39013
- 39017
- 39041-39045
- 1128-1129
- 59013-59014

## References

- [SAP HANA Express - Docker Hub](https://hub.docker.com/_/sap-hana-express-edition)
- [SAP HANA - Install Using Docker](https://developers.sap.com/tutorials/hxe-ua-install-using-docker.html)
