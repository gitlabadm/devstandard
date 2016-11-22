Administration
===============

There is for GitLab Administrator. How to install/configure/upgrade/maintain GitLab. If you chose gitlab.com to host your source code, then
you can ignore this secion.


Install
--------

Go to https://about.gitlab.com/downloads/ and select operating system, follow the guide.
After that, open the browser and type the address.


Configuration
-------------

Edit `/etc/gitlab/gitlab.rb` then run `gitlab-ctl reconfigure`

Upgrade
--------

Update is very easy, if the operating system is CentOS.

.. code-block:: bash

  $ sudo yum install gitlab-ce

Maintain
---------

For backup: please use the scripts: https://github.com/gitlabadm/auto-gitlab-backup
