# Setup PHP and Postgres with Ansible

Add a .env file

```env
username="yourusername"
password="password"
bridge="Intel(R) Ethernet Connection (2) I219-V"
```

Change the variable in vars/default.yml

```yml
---
app_user: "vagrant"
http_host: "geo-wiki.local"
http_conf: "geo-wiki.conf"
http_port: "80"
disable_default: true
db_name: "vagrant"
db_user: "vagrant"
db_password: "vagrant"
```
