Role Name
=========
Ansible role for Celery Flower setup

Requirements
------------
Ansible 1.2 or later

Role Variables
--------------
- flower_version: Version of flower to install
- flower_user: User to run flower
- flower_group: Group to run flower
- flower_app_name: Application name
- flower_app_module: Set to application module
- flower_pre_exec: Commands to execute before starting celery
- flower_env: Default environment variables
- flower_prefix: Set to installation prefix
- flower_work_dir: Working directory
- flower_run_dir: Run directory
- flower_log_dir: Log directory
- flower_log_level: Log level
- flower_basic_auth_enabled: Basic Auth flag
- flower_basic_auth: Basic Auth params
- flower_url_prefix_enabled: URL prefix flag
- flower_url_prefix: URL prefix
- flower_broker: Broker URL
- flower_host: Run the http server on a given address
- flower_port: Run the http server on a given port

Dependencies
------------
None

License
-------
MIT

Author Information
------------------
Rajtilak Indrajit

References
------------------
- https://github.com/Stouts/Stouts.celery
- http://bespokebytes.com/start-getting-up-and-running-with-upstart/
