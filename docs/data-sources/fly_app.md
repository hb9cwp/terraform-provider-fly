---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "fly_app Data Source - terraform-provider-fly-official"
subcategory: ""
description: |-
  Retrieve info about graphql app
---

# fly_app (Data Source)

Retrieve info about graphql app

## Example Usage

```terraform
data "fly_app" "example" {
  name = "hellofromterraform"
  depends_on = [
    fly_app.exampleApp
  ]
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String) Name of app

### Read-Only

- `appurl` (String)
- `currentrelease` (String)
- `deployed` (Boolean)
- `healthchecks` (List of String)
- `hostname` (String)
- `id` (String) The ID of this resource.
- `ipaddresses` (List of String)
- `status` (String)


