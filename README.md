Gerrit Warden
============

The purpose of this code is to stream events from gerrit via ssh and trigger
workflow transitions in Jira.
Code is dependent on gerritlib and python-jira modules which have to be installed
separately if you are planning to run it from master branch.

Main configuration files are in etc folder:
gerritwarden.conf - sets connection to gerrit and location of other config
jiras.yml - sets connection setting to jira and custom field used for code reviews
projects.yml - sets projects in gerrit which should be watched and desired
transition states for those projects
