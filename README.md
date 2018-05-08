ac-operations
NW-T
====

## Overview
 - Its Ansible Playbook for operation management.

## Description
 - Add, change, and delete AWS Route 53.
 - Add, change, and delete Cisco NW configuration

## git init setting
1. ssh config
$ cat << EOF > $HOME/.ssh/config
Host github.com
  User ymatsu
  Port 22
  HostName github.com
  IdentityFile ~/.ssh/ac_operations_git_id_rsa
  HostName github.com
  IdentitiesOnly yes
EOF

2. get ssh-key
wget https://s3-ap-northeast-1.amazonaws.com/native-application/ac_operations_git_id_rsa -O $HOME/.ssh/ac_operations_git_id_rsa

3. git config
$ git config --global user.name "First-name Family-name"
$ git config --global user.email "username@example.com"
$ git config --global core.editor 'vim -c "set fenc=utf-8"'
$ git config --global color.diff auto
$ git config --global color.status auto
$ git config --global color.branch auto
$ git config --global push.default simple
$ git config --global --unset push.default
$ git config --global core.quotepath false
$ git config --global -l

4. test commit
$ echo 'Hello World!' >> hello.txt
$ git status -s
$ git add hello.txt
$ git commit -m "$USER@ first commit"
$ git log
$ git push origin master

## Demo

## VS. 

## Requirement

## Usage

## Install

## Contribution

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[tcnksm](https://github.com/tcnksm)
