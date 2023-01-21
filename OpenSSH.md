# OpenSSH

## ssh-keygen

#### Generate SSH key pair

```
ssh-keygen -a 512 -C "Comment Here" -f ./outkeyfile -t ed25519 -Z chacha20-poly1305@openssh.com
```
