---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "openwebui_knowledge Data Source - openwebui"
subcategory: ""
description: |-
  Knowledge data source for OpenWebUI
---

# openwebui_knowledge (Data Source)

Knowledge data source for OpenWebUI



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String) Name of the knowledge base to look up

### Read-Only

- `access_control` (String) Access control type ('public' or 'private')
- `access_groups` (List of String) List of group IDs with access
- `access_users` (List of String) List of user IDs with access
- `data` (Map of String) Additional data for the knowledge base
- `description` (String) Description of the knowledge base
- `id` (String) Knowledge identifier
- `last_updated` (String) Timestamp of the last update
