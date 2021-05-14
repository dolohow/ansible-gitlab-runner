Ansible Gitlab Runner
=====================

This is **ansible playbook** that installs **gitlab runner** on desired
server.

It:
  * puts your ssh into your server
  * installs docker
  * installs gitlab-runner

I recommend service
[DigitalOcean](https://www.digitalocean.com/?refcode=2bb76a64c889&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)
for vps servers.

Put your hosts into `hosts` file

To installl, run:
```
ansible-playbook -i hosts site.yml
```
