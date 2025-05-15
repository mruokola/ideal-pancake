### "ideal-pancake"

It's a Github-generated repository name, but the purpose was to provide a base module/template of sorts for the `reimagined-dollop` repo

#### Development

All the relevant Ansible code is in `local.yml`, with variables being loaded from `group_vars/all.yml`

#### Deployment

##### Complete

```sh
ansible-pull -U https://github.com/mruokola/ideal-pancake.git
```

##### Setup/OS preparations

```sh
ansible-pull -U https://github.com/mruokola/ideal-pancake.git -t setup
```

