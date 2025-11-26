# Ultimative-Kali-Setup

Ultimative-Kali-Setup is a Ansible projekt to automate the set up of a Kali Linux enviroment with additional tools and useful configs.


## Installation & Usage

Configure your Ansible inventory to include your Kali Linux machine.
Run the playbook:

```bash
ansible-playbook playbooks/kali.yml -i inventory.yml
```

## Features

This setup includes the following features:

- Customized Tmux configuration for better terminal management.
- Arsenal from Orange Cybverdefense pre-installed.
- Various tools such as feroxbuster, seclists and more installed.
- Virtual python environments for tool isolation.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

MIT