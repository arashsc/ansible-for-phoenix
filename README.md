This is an ansible project to release Elixir/Phoenix project to CentOS server.

# Usage

## Set your environment
Please grep 'TODO', then replace with proper text fits your environment.

## Prepare New Server
```
$ ansible-playbook -i production centos.yml -u root
```

## Deploy app
```
$ ansible-playbook -i production deploy.yml -u deploy
```
