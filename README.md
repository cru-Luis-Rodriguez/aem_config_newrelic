aem_confi_newrelic Cookbook
=======================
This recipe is use to configure newrelics java agent for adobe's AEM.

Requirements
------------
depends on newrelic recipe and pre-installed instance of AEM 

#### packages

Attributes
----------
TODO: List your cookbook attributes here.

e.g.
#### aem_config_newrelic::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['aem_config_newrelic']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

Usage
-----
#### aem_config_newrelic::default
TODO: Write usage instructions for each cookbook.

e.g.
Just include `aem_config_newrelic` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[aem_config_newrelic]"
  ]
}
```

Contributing
------------
TODO: (optional) If this is a public cookbook, detail the process for contributing. If this is a private cookbook, remove this section.

e.g.
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Luis A.Rodriguez
