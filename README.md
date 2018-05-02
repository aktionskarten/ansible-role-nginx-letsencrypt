nginx-letsencrypt
=================

An ansible role for requesting ssl certificates through acme-tiny and nginx.


Role Variables
--------------

Only available role variable is letsencrypt\_fqdn. It should be a list of strings
of fqdns for which you want to request a certificate.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
    - hosts: servers
      roles:
         - { role: acme-tiny, lets_encrypt_fqdn: ['www.foo.bar'] }
```


License
-------

BSD
