roles
├── jenkins
└── nginx
    ├── files
    │   └── index.html
    ├── handlers
    │   └── main.yaml
    ├── tasks
    │   └── main.yaml
    ├── templates
    └── vars
        └── main.yaml

================= add host in /root/.ssh directoory =========
cd /root/.ssh
vim worker.pem
vim config
Host jenkins
    HostName 172.31.36.33
    User ec2-user
    IdentityFile ~/.ssh/worker.pem
========== project structure ======
'''
ansible
├── ansible.cfg
├── index.html
├── inventory
├── playbooks
│   ├── jenkins.yaml
│   └── webserver.yaml
├── readme.md
├── roles
│   ├── jenkins
│   └── nginx
│       ├── files
│       │   └── index.html
│       ├── handlers
│       │   └── main.yaml
│       ├── tasks
│       │   └── main.yaml
│       ├── templates
│       └── vars
│           └── main.yaml
├── templates
│   └── index.html.j2
└── variables
    └── vars.yaml
'''



