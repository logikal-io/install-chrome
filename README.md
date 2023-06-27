Install Chrome
==============
GitHub Action for installing Chrome and ChromeDriver.

**Note:** This action has been **deprecated**. You can migrate to using the more flexible
[run-logikal-playbook action](https://github.com/marketplace/actions/run-logikal-playbook) instead:

```yaml
- uses: logikal-io/run-logikal-playbook@v1
  with:
    roles: chrome
    vars: '{"chrome_package_version": "{version}"}'
```

Usage
-----
```yaml
steps:
  - uses: logikal-io/install-chrome@v1
    with:
      version: {version}
```

Inputs
------
`version`: Required, the version to install.

License
-------
This GitHub Action is licensed under the MIT open source license.
