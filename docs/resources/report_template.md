---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "shoreline_report_template Resource - terraform-provider-shoreline"
subcategory: ""
description: |-
  Shoreline report_template. A resource report template. Note: Configure privilege (in Shoreline) to create report template objects.
---

# shoreline_report_template (Resource)

Shoreline report_template. A resource report template. Note: Configure privilege (in Shoreline) to create report template objects.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `blocks` (String) The JSON encoded blocks of the report template.
- `name` (String) The name/symbol for the object within Shoreline and the op language (must be unique, only alphanumeric/underscore).

### Optional

- `display_name` (String) A user friendly name shown in the UI.

### Read-Only

- `id` (String) The ID of this resource.
- `type` (String) The type of object (i.e., Alarm, Action, Bot, Metric, Resource, or File).