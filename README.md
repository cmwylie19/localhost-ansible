# Ansible Refresher
_Small playbook to download some packages and ping a webserver runningon localhost:8080 to make sure it is up_

The reason for this repo is not to forget ansible.   

## Try it
npx http-server . -p 8080

```
ansible-playbook playbook.yml
```

Then enter your mac os password and it will install the packages listed in below
  - speedtest-cli
  - archey
  - htop
  - nmap
  - websocat
