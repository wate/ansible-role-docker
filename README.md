docker
=================

Setup docker

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `docker_packages`

インストールするパッケージ

#### `docker_cfg`

Dockerの設定

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `docker_apt_key_url`

#### `docker_apt_key_dest`

#### `docker_user`

#### `docker_group`

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: docker
```

License
--------------

Apache License 2.0
