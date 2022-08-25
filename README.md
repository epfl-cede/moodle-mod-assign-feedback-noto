# moodle-mod-assign-feedback-noto
Jupyterhub plugin for Moodle: feedback module

This repository contains a plugin made for Moodle 3.9.
It is designed to make the communication from Moodle to a JupyterHub installation possible, allowing Moodle users to access their Jupyter files from Moodle - and more.

Please note: this is the plugin for feedback from teachers to students. There is a second plugin for submissions from students to teachers which has to be installed separately. See below for more information.

## assignfeedback plugin

This plugin is still under development ; the current version allows teachers to download all students' submissions in one click into the teacher's Jupyter workspace.

## assignsubmission plugin

See [epfl-cede/moodle-mod-assign-submission-noto](https://github.com/epfl-cede/moodle-mod-assign-submission-noto).

# Installation

Plugins' content need to be copied over to:
```
[moodle_root]/mod/assign/feedback/noto
```
on the Moodle server.

# API

On the JupyterHub side, an API needs to be deployed on a server that has access to all user's files - typically the file server of the JupyterHub installation.

See this repository for the API: [epfl-cede/jupyterhub-fileserver-api](https://github.com/epfl-cede/jupyterhub-fileserver-api)
