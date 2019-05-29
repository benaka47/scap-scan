# scap-scan
### Usage
Example Playbook
----------------

  ```yaml
  - hosts: all
    roles:
       - { role: scap-scan }
  ```

You need to use different `inventory` depending on your use case.  
For example use case #1, you should use this kind of `inventory` :
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
