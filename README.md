# POC
In many cases, normal users belonging to the Docker﻿ group are vulnerable to privilege escalation.
This exploit creates a container with a mount of the host system root, copies the normal user's public SSH key to the root's authorized_keys file, allowing passwordless SSH access as root.

### Execution

```
  git clone https://github.com/666aalexx/DockerPrivEsc.git

  cd DockerPrivEsc
  
  chmod +x exploit.sh
  
  ./exploit.sh
```
