Flask-Setup
========================

This role is for configuring the basic server requirements for a flask application which is further servred via Uwsgi and Nginx

#Example Playbook

Including an example of how to use this role (for instance, with variables passed in as parameters) is always nice for users too:

---
- hosts: localhost
  roles:
    - { role: "flask-setup" }

#What This Role Will Do

* Create a user which will run this flask based application
* Install certain packages which are required at server level for a flask based application.
