---
date: 2016-03-11T10:34:44-05:00
title: "doit compute ssh"
slug: doit_compute_ssh
url: /commands/doit_compute_ssh/
---
## doit compute ssh

ssh to droplet

### Synopsis


ssh to droplet

```
doit compute ssh <droplet-id | host>
```

### Options

```
      --ssh-key-path string   path to private ssh key (default "/Users/bryan/.ssh/id_rsa")
      --ssh-port int          port sshd is running on (default 22)
      --ssh-user string       ssh user (default "root")
```

### Options inherited from parent commands

```
  -t, --access-token string   DigitalOcean API V2 Access Token
  -o, --output string         output formt [text|json] (default "text")
  -v, --verbose               verbose output
```

### SEE ALSO
* [doit compute](/commands/doit_compute/)	 - compute commands

###### Auto generated by spf13/cobra on 11-Mar-2016