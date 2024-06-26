---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "secureworkload_scope Data Source - terraform-provider-secureworkload"
subcategory: ""
description: |-
  Data source for fetching scopes from secure-workload
  An example is shown below:
  hcl
  data "secureworkload_scope" "scope" {
      exact_name = "RootScope:ChildScope"
  }
---

# secureworkload_scope (Data Source)

Data source for fetching scopes from secure-workload

An example is shown below: 
```hcl
data "secureworkload_scope" "scope" {
	exact_name = "RootScope:ChildScope"
}
```



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `exact_name` (String) Name of the scope

### Optional

- `exact_short_name` (String) Short name of the scope
- `vrf_id` (Number) The VRF ID of this resource

### Read-Only

- `id` (String) The ID of this resource


