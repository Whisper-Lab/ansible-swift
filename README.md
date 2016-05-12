Swift
=========

An Ansible role for installing Apple Swift.

Requirements
------------

Ubuntu 12.04 or higher

Role Variables
--------------

- `ansible_swift_version`
  - default: `2.2-SNAPSHOT-2016-01-06-a`
- `ansible_swift_platform`
  - default: `ubuntu15.10`
- `ansible_swift_platform_short`
  - default: `ubuntu1510`
- `ansible_swift_root`
  - default: `/opt/swift`

Example Usage
-------

```
  vars:
    ansible_swift_version: DEVELOPMENT-SNAPSHOT-2016-05-03-a
    ansible_swift_platform: ubuntu14.04
    ansible_swift_platform_short: development/ubuntu1404
    ansible_swift_root: /opt/swift

  roles:
    - ansible-swift
```

License
-------

MIT

Author Information
------------------

Alexey Pustobaev
