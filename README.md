# code-guardian-cookbook

Enable a local VM for sonar/jenkins.

## Supported Platforms

Tested on windows/mac.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['code-guardian']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### code-guardian::default

Include `code-guardian` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[code-guardian::default]"
  ]
}
```

## License and Authors

Author:: David Navarro (davengeo@yahoo.es)
