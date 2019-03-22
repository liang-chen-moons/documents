# Active Directory (LDAP)

LDAP (Active Directory) Authentication is disabled by default. To make it work, we should **disable multi-tenancy** since LDAP auth is not used in a multi-tenant system normally. See [server side](Development-Guide-Core.md) to enable LDAP. Once we enable, we can see **LDAP settings** section in the settings page:

<img src="D:/Github/documents/docs/en/images/tenant-settings-ldap-1.png" alt="LDAP Settings" class="img-thumbnail" />

We can check "**Enable LDAP Authentication**" to enable it. If the server works in domain and application runs with a domain user or local system, then generally even **no need** to set Domain name, user and password. You can logout and then login with your **domain user name and password**. If not, you should set these credentials.

## Next

- [Maintenance](Features-Angular-Maintenance)