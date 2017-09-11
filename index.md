# kerberos

---

1.安装组件

`yum install openldap openldap-servers openldap-clients openldap-devel compat-openldap db4 db4-utils db4-devel cyrus-sasl* krb5-server-ldap`

2.配置文件

>kerberos 

- /etc/krb5.conf
- /var/kerberos/krb5kdc/kdc.conf
- /var/kerberos/krb5kdc/kadm5.acl
- /var/kerberos/krb5kdc/service.keyfile
- **/var/kerberos/krb5kdc/.k5.58os.org**

>openldap

- /etc/openldap/reldap.sh
- /etc/openldap/slapd.conf

