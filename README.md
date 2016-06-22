## OpenLDAP Agent Install

1. Download the latest tagged version from `https://github.com/ocadotechnology/newrelic-plugin-openldap/tags`
2. Extract to the location you want to run the openldap agent from
3. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
4. Edit `config/newrelic_plugin.yml` and replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
5. Enable the cn=monitor subtree in your OpenLDAP server
6. Edit `config/newrelic_plugin.yml` and your OpenLDAP server details
7. run `./newrelic_openldap_agent`
