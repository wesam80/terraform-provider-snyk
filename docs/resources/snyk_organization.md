---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "snyk_organization Resource - terraform-provider-snyk-wes"
subcategory: ""
description: |-
  Provides Snyk Organizations https://docs.snyk.io/snyk-admin/manage-groups-and-organizations/whats-a-snyk-organization
---

# snyk_organization (Resource)

Provides Snyk [Organizations](https://docs.snyk.io/snyk-admin/manage-groups-and-organizations/whats-a-snyk-organization)



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String) The name of the organization

### Optional

- `group_id` (String) The group ID. The API_KEY must have access to this group.
- `source_organization_id` (String) The id of an organization to copy settings from.

### Read-Only

- `id` (String) Snyk organization id
- `slug` (String) The slug of the organization