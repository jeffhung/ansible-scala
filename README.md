# Ansible Role: jeffhung.scala

Ansible playbook for installing Scala on CentOS/Debian Linux

Install this playbook:

	ansible-galaxy install jeffhung.scala


## Role Variables

### `scala_version`

Default: `2.11.8`

Set which Scala version to use.

Could be:

* `2.11.8`

### `scala_environment`

Default: `devel`

Which environment to deploy.

Could be:

* `devel`: provision devel-time environment for developing with Scala
* `build`: provision build-time environment for packaging Scala

### `scala_cache_dir`

Cache directory for holding downloaded/generated files.

The default is `/vagrant/files` so cache persist between boxes.


## License

BSD

