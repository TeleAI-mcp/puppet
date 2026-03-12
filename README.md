Puppet
======

[![License](https://img.shields.io/github/license/puppetlabs/puppet.svg)](https://github.com/puppetlabs/puppet/blob/main/LICENSE)
[![Test](https://github.com/puppetlabs/puppet/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/puppetlabs/puppet/actions/workflows/test.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/puppetlabs/puppet/branch/main/graph/badge.svg?token=UaJlKJuGya)](https://codecov.io/gh/puppetlabs/puppet/branch/main)

Puppet, an automated administrative engine for your Linux, Unix, and Windows systems, performs administrative tasks
(such as adding users, installing packages, and updating server configurations) based on a centralized specification.

Documentation
-------------

Documentation for Puppet and related projects can be found online at the
[Puppet Docs Site](https://puppet.com/docs/puppet/latest/puppet_index.html).

Puppet manual
-------------

The official Puppet manual is available online [here](https://puppet.com/docs/puppet/latest/puppet_index.html).

Installation
------------

The Puppet agent and server packages can be installed in a variety of ways:

* On Linux, using [puppet-agent](https://puppet.com/docs/puppet/latest/install_agents.html) packages
* On Windows, using [msi packages](https://puppet.com/docs/puppet/latest/install_windows.html)
* On macOS, using [pkg packages](https://puppet.com/docs/puppet/latest/install_osx.html)

Source Installation
-------------------

Puppet can be installed via RubyGems:

    gem install puppet

Or via source:

    git clone https://github.com/puppetlabs/puppet.git
    cd puppet
    bundle install
    bundle exec rake install

Contributing & License
----------------------

Puppet is licensed under the [Apache 2 license](https://github.com/puppetlabs/puppet/blob/main/LICENSE).
Check out the [contributing guide](https://github.com/puppetlabs/puppet/blob/main/CONTRIBUTING.md) to get started.

Related Projects
----------------

1. related project [ansible](https://github.com/ansible/ansible)
2. related project [salt](https://github.com/saltstack/salt)
