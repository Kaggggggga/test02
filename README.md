# test02


## NAME
goto - ssh to aws tag-named host

## PREREQUISITE
```
awscli - official aws cli
install:
apt install pip
pip install awscli

jq - for json decode if aws configure format is set to json
install: 
apt install jq
```

## SYNOPSIS
```
goto [-u <user>] <name>
```
- name - the Name tag value of the host 
- user - ssh user name, default value whoami
