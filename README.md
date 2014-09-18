# et_travis_demo-cookbook

A Travis Demonstration Cookbook

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['et_travis_demo']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### et_travis_demo::default

Include `et_travis_demo` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[et_travis_demo::default]"
  ]
}
```

## License and Authors

Author:: EverTrue, Inc. (<eric.herot@evertrue.com>)
