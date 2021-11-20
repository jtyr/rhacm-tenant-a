Red Hat ACM - Tenant A
======================

This repo contains Red Hat ACM resources to onboard applications for Tenant A.

Content
-------

- `chartmuseum` - onboard Chartmuseum application into the `tenant-a` namespace
  and using placement rule from the same namespace (working)
- `chartmuseum-ns` - onboard Chartmuseum application into `chartmuseum-ns`
  namespace and using placement rule from the same namespace (not working -
  everything installed into the `tenant-a` namespace)
- `chartmuseum-pr` - onboard Chartmuseum application into the `tenant-a`
  namespace and using placement rule from the `tenants` namespace (not working -
  placement rule not found)

Author
------

Jiri Tyr
