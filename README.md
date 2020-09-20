stocks-server
=========

Installs and configures stocks-server

Requirements
------------

None.

Role Variables
--------------

| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`stocks_db_host` | localhost | DB host
`stocks_db_port` | 5432 | DB port
`stocks_db_name` | stocks | DB name
`stocks_db_user` | stocks | DB user
`stocks_db_password` | stocks | DB password

Dependencies
------------

A `stocks-server` package present in the apt repositories. You may have to build
this yourself from the [official
repository](https://github.com/F1rst-Unicorn/stocks).

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
