# Docker Image Packaging for Development

## YYYYMMDD.Y.Z - TBC

### Major Changes

  - Upgrade minimal Ansible community package support to 4.1.0

## 20210602.1.1 - 2021-06-02

### Major Changes

  - Initialize with `verify.yml` with first start
  - Upgrade minimal Ansible support to 4.0.0

## 20210412.1.1 - 2021-04-12

  - Packaging by Packer Docker builder and Ansible provisioner in single
    layer
  - Handle `ENTRYPOINT` with
    [catatonit](https://github.com/openSUSE/catatonit)
  - Handle `CMD` with SSHD
