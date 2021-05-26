# Docker Image Packaging for Development

## YYYYMMDD.Y.Z - TBC

### Major Changes

  - Upgrade minimal Ansible support to 4.0.0
## 20210412.1.1 - 2021-04-12

  - Packaging by Packer Docker builder and Ansible provisioner in single layer
  - Handle `ENTRYPOINT` with [catatonit](https://github.com/openSUSE/catatonit)
  - Handle `CMD` with SSHD
