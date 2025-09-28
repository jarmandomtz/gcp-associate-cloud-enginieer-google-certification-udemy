# GCP General concepts

## Regions and zones

Regions: 40 and growing
- https://cloud.google.com/about/locations#lightbox-regions-map

Zones: Deployment areas in a region, named like Region + letter. Each region has 3 or more zones

Zones connected in a region: Low latency links

Cluster: Physical Compute, Storage, and Network in a Zone (Data center)

Zone to cluster mapping: All infra from specific client in specific Cluster X in a Zone not visible to customer. For more organizations, compute engine ensures that all projects in an organization have a consistent zone to cluster mapping

High Availability across regions: Using a Global External Application Load Balancer HTTP
