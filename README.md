RDO
===
This role installs and sets up the RDO repositories.

Requirements
------------
None


Role Variables
--------------
You can change the name of the release by setting the `openstack_rdo_release`
variable, it currently defaults to `newton` which is the latest release.


Dependencies
------------
None


Example Playbook
----------------
You can easily add this role and choose to specific the release anywhere you
want, but you'd probably want this in `group_vars` so all of your environment
runs the same release.

    - hosts: servers
      roles:
      - vexxhost.openstack-rdo

License
-------
Apache 2.0


Author Information
------------------
Mohammed Naser <mnaser@vexxhost.com>
