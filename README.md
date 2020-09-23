---
Default values
---
instantclient_libaio1_version: "0.3.112-3"
instantclient_oracle_package_src: "/home/gitlab-runner"
instantclient_oracle_package_dest: "/root/"
instantclient_oracle_packages:
    - {filename: 'oracle-instantclient12.2-basic_12.2.0.1.0-2_amd64.deb'}
    - {filename: 'oracle-instantclient12.2-devel_12.2.0.1.0-2_amd64.deb'}
    - {filename: 'oracle-instantclient12.2-sqlplus_12.2.0.1.0-2_amd64.deb'}
instantclient_oracle_lib: "/usr/lib/oracle/12.2/client64/lib/"
instantclient_oracle_home: "/usr/lib/oracle/12.2/client64"

