# ansible-geomesa-accumulo-ubuntu

# Description

**ansible-geomesa-accumulo-ubuntu** is a simple [Ansible](https://www.ansible.com/) role for installing [GeoMesa](http://www.geomesa.org/) for [Accumulo](https://accumulo.apache.org/) on an Ubuntu machine.

# Usage

**Playbook**

When installing GeoMesa for Accumulo, be sure to install the relevant dependencies, e.g., [Accumulo](https://accumulo.apache.org), [Zookeeper](https://zookeeper.apache.org), and [Hadoop](https://hadoop.apache.org).

For an advance install, please consult the official GeoMesa documentation on [Installing GeoMesa Accumulo](http://www.geomesa.org/documentation/current/user/accumulo/install.html).


**Playbook**

Your Ansible playbook should look something like this:

```
...
roles:
  - ansible-java-ubuntu
  - ansible-zookeeper-ubuntu
  - ansible-hadoop-ubuntu
  - ansible-accumulo-ubuntu
  - ansible-geomesa-accumulo-ubuntu
...
```

# Contributing

[Spatial Current, Inc.](https://spatialcurrent.io) is currently accepting pull requests for this repository.  We'd love to have your contributions!  Please see [Contributing.md](https://github.com/spatialcurrent/ansible-geomesa-accumulo-ubuntu/blob/master/CONTRIBUTING.md) for how to get started.

# License

This work is distributed under the **MIT License**.  See **LICENSE** file.
