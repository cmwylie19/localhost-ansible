# Ansible Refresher
_The reason for this repo is so that I don't forget ansible_

_Small playbook to download some packages and ping a webserver runningon localhost:8080 to make sure it is up_

The reason for this repo is not to forget ansible.   

## Try it
In one terminal
```
npx http-server . -p 8080
```

```
ansible-playbook playbook.yml
```

Then enter your password that you use for sudo and it will install the packages listed in below
  - speedtest-cli
  - archey
  - htop
  - nmap
  - websocat
