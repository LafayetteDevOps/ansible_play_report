# ansible_play_report
An Ansbile play for the automatic generation of reports and emailing through a relay host.

Requirements:
-----

This Ansible play requires variables, set up under the `vars:` section, and several `Ansible facts`, within `reports.yml`. 

Dependencies:
-----

This play requires the `community.general` collection, `Postfix` to be installed and configured on the Automation Platform, and an email relay host.

Ansible play:
-----
The Ansble play will be called within `reports.yml` connection block.
