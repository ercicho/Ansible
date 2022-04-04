<h2 align="center">Ansible</h2>
  
<h4 align="Left">Ansible Commands</h4><br />

#Check the syntax of your code

```diff
- ansible-playbook --syntax-check sample.yml
```

#Check the syntax of your code passing variable that are expected

```diff
- ansible-playbook --syntax-check -e"passwd_in_hosts=localhost" sample.yml
```

#Check the syntax of your code and result. 0 mean no error

```diff
- ansible-playbook --syntax-check sample.yml
- echo $?
```
