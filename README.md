# vbox-remote
virtualbox remote management via ssh

allows one to manage virtualbox via a docker container or even from a remote host.

if using packer, vagrant, terraform
docker requires bind mounts to exchange files.
if running from a remote host sshfs or any other network share will do.
