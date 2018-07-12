# pysshops

pysshops is a comodity pacakge to build python operations tools working on ssh and powered by [paramiko](https://github.com/paramiko/paramiko)

## Quickstart
```python
from pysshops import SshOps
sshops = SshOps('hostname.domain.it', 'username')
with sshops as ssh:
    ssh.remote_command('ls -l /var/tmp')
```

## Features
* simple
* powered by rock-solid paramiko