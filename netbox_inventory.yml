plugin: netbox.netbox.nb_inventory

api_endpoint: "YOUR_NETBOX_API_URL"
token: "YOUR_NETBOX_API_TOKEN"

validate_certs: false
config_context: true
interfaces: true
group_names_raw: true

group_by:
  - devices_roles
  - platforms
  - device_types
  - tenants
  - sites
  - racks
  - tags

query_filters: []

device_query_filters:
  - has_primary_ip: "true"

flatten_custom_fields: true
