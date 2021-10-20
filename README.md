# Install Ansible with Ansible

Role for installing ansible

## Optional Parameters

 * `ansible_pip_user` - User installing ansible with pip (ansible by default)

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

Run the following from the test directory:

### Initial Install
```
vagrant up
```

### Reapply provisioning
```
vagrant provision
```

## TODO

 * Install specified python version. role?
