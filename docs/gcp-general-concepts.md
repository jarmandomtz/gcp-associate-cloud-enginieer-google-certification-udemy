# GCP General concepts

## Regions and zones

Regions: 40 and growing
- https://cloud.google.com/about/locations#lightbox-regions-map

Zones: Deployment areas in a region, named like Region + letter. Each region has 3 or more zones

Zones connected in a region: Low latency links

Cluster: Physical Compute, Storage, and Network in a Zone (Data center)

Zone to cluster mapping: All infra from specific client in specific Cluster X in a Zone not visible to customer. For more organizations, compute engine ensures that all projects in an organization have a consistent zone to cluster mapping

High Availability across regions: Using a Global External Application Load Balancer HTTP

## Cloud shell

Reference: https://cloud.google.com/shell

- A lot of tools installed
- 5Gb of persistent disk storage for $HOME
- **Online code editor**: Using cloud shell editor

## gcloud

Few of the GCP service have their own CLI tools
- Cloud Bigtable: cbt
- Cloud BigQuery: bq
- Cloud Storage:  gsutil (old), gcloud recommended going forward
- Kubernetes:     kubectl

Rest of services are considered in gcloud

**Install**
Cloud SDK: https://cloud.google.com/sdk/docs/install

