# React Native Dev environment using `Vagrant`

## Prerequisites
1. [Vagrant]
2. [VirtualBox]
3. (Optional) [Cygwin]
4. (Optional) [VS Code]

## Usage

```
vagrant up
vagrant ssh-config
copy output into ssh config
use vs code remote extension pack to remote in

ssh-keygen -t ed25519 -C "youremail@email.com"
add pub key to https://github.com/settings/keys
```

<!-- Refs -->
[cygwin]: https://www.cygwin.com/index.html
[vagrant]: https://developer.hashicorp.com/vagrant
[virtualbox]: https://www.virtualbox.org/
[vs code]: https://code.visualstudio.com/
