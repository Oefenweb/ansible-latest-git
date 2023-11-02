## latest-git

[![CI](https://github.com/Oefenweb/ansible-latest-git/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-latest-git/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-latest--git-blue.svg)](https://galaxy.ansible.com/Oefenweb/latest_git)

Set up the latest version of git in Ubuntu systems.

#### Requirements

* `python-apt`

#### Variables

* `latest_git_install`: [default: `[git]`]: Packages to install (from PPA repository)

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.latest-git
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-latest-git/issues)!
