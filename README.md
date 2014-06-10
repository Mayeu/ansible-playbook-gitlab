Gitlab
======

Install and configure the Omnibus package of Gitlab.

The documentation about this package is here:
https://gitlab.com/gitlab-org/omnibus-gitlab/blob/master/README.md

This playbook only install Gitlab, not the "mandatory" mail server.

Role Variables
--------------

Only two variables are definied:

  * `gitlab_pkg_name`: the name of the Gitlab package to install
  * `gitlab_pkg_url`: the url to download the package from

You can update this variable using this page: https://www.gitlab.com/downloads/

You will need to add your configuration in your `files` folder, under a `gitlab` folder. ie: `folder/gitlab/gitlab.rb`.

License
-------

BSD
