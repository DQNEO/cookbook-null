# Chef Null Cookbook

This cookbook does nonthing at all.

# USAGE

In you `Berksfile`

```ruby
source "https://supermarket.chef.io"

cookbook 'hello', github: 'DQNEO/cookbook-null
```

in your nodes/$hostname.json file,

```json
{
  "run_list": [
    "null"
  ]
}
```
