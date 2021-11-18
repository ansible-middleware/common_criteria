# Common Criteria Collection for Ansible

Collection to handle common criteria certification.

<!--start requires_ansible-->
## Ansible version compatibility

This collection has been tested against following Ansible versions: **>=2.9.10**.

Plugins and modules within a collection may be tested with only specific Ansible versions. A collection may contain metadata that identifies these versions.
<!--end requires_ansible-->


## Included content

Click on the name of a plugin or module to view that content's documentation:

### Roles
Name | Description
--- | ---
jws_common_criteria | Handle'scommon criteria certification.
wildfly_commom_criteria | Handle's wildfly configuraion.

## Installation and Usage

### Installing the Collection from Ansible Galaxy

Before using the collection, you need to install it with the Ansible Galaxy CLI:

    ansible-galaxy collection install middleware_automation-common_criteria-*.tar.gz

You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml`, using the format:

```yaml
---
collections:
  - name: middleware_automation.common_criteria
```
### Using via GitHub Action
A GitHub action which is uses this role is provided by the Red Hat Containers Community of Practice (CoP)
- https://github.com/redhat-cop/github-actions/tree/master/common_criteria

## License

Apache License v2.0 or later

See [LICENCE](LICENSE) to view the full text.
