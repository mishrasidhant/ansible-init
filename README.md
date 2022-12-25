# ansible-init
Learning ansible

## Configs
- `inventory` specifies what file to use as inventory
- ``

## Commands
> Execute a command (module name) on a group using a custom inventory file
```
ansible <group> -i <path to custom inventory file> -m <module_name>
```

> Ping a group of hosts (all) using ping module
```
ansible all -m ping
```

> Gather facts about remote hosts 
```
ansible all -m gather_facts
```

> Gather facts about a specific host
```
ansible all -m gather_facts --limit <hostname/ip>
```
