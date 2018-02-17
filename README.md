Workstation Setup
=================

Do not run inside python virtual environment, the pip packages use --user
and this is not supported in a virtual environment.  Typically just install
ansible with dnf and then uninstall when finished.

	ansible-playbook -i localhost, fedora.yml -K
