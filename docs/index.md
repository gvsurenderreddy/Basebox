# Enrise Basebox

[![Documentation](https://readthedocs.org/projects/enrise-basebox/badge/?version=master)](http://enrise-basebox.readthedocs.org/)

This box serves as a standardized version of Vagrant box and should be used for new projects.

Provisioning is done using [Saltstack](http://saltstack.org), which uses various default
[Saltstack-formulas](https://github.com/saltstack-formulas) and
[custom Enrise formulas](https://github.com/enrise/?query=formula) to provide featurepacks.

This box provides a default web-stack (ZendServer 7.0 + Nginx + MariaDB) using the
[enrise/vhosting-formula](https://github.com/enrise/vhosting-formula) formula.
The box should be build on a Debian or Ubuntu VM.

Further requirements (e.g. Node, Postgres, Composer etc) can be added by the user of this box.
