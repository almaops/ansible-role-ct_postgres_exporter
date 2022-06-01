# Checklist for repo created from template
* Change ROLENAME across all text files in your repository
* Change AUTHORNAME to your "Firstname Lastname" in meta
* Define role dependencies in meta
* Remove this section, once you created a repo

# almaops.ROLENAME
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)


# Requirements

# Role variables
Please refer to [defaults/main.yml](./defaults/main.yml) for full list of available variables. 

# Dependencies
None

# Example playbook
```
- hosts:
    - servers
  become: true
  roles:
    - role: almaops.ROLENAME
```

# License
[MIT](./LICENSE)

# Contributors
[Firstname Lastname](https://github.com/_)