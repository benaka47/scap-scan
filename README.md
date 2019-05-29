# scap-scan
### Usage
Example Playbook
----------------

  ```yaml
  - hosts: all
    roles:
       - { role: scap-scan }
  ```

Inventory example.  

```ini
[masters]
master0.example.com
master1.example.com
master2.example.com

[nodes]
node0.example.com
node1.example.com
node2.example.com
```
