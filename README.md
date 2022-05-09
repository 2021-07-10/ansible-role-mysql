# Ansible Role: MySQL 8.x

Installs MySQL 8.x on Ubuntu 20.04

## Requirements

None

## Role Variables


* `mysql_user_name`: 用户名
* `mysql_user_password`: 密码
* `mysql_databases`: 数据库



## Dependencies

None

## Example Playbook

```
- hosts: servers
  roles:
    - role: guxiaobai.mysql
      mysql_user_name: 'bettle'
      mysql_user_password: 'example'
      mysql_databases: 
       - 'bettle_development'
       - 'bettle_test'
       - 'bettle_production' 
```

## License

BSD

