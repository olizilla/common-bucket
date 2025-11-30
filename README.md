# Common Bucket

_What should S3-Compatible really mean?_

Common Bucket is a community initiative to define a strict, minimal subset of the S3 API to ensure true interoperability across cloud providers and open-source tools.

A clearly defined subset of the 100+ S3 operations. Write code once. Run it on AWS, Cloudflare, MinIO, or your own server. Any common bucket will do.

## Implementors

### Open Source Tools

| Tool | Tier 1 (Core) | Tier 2 (Reliability) | Tier 3 (Ecosystem) | Documentation |
| :--- | :---: | :---: | :---: | :--- |
| **MinIO** | ✅ | ✅ | ✅ | [MinIO S3 API](https://min.io/docs/minio/linux/reference/minio-server/minio-server.html#s3-api-compatibility) |
| **Ceph (RGW)** | ✅ | ✅ | ✅ | [Ceph S3 API](https://docs.ceph.com/en/latest/radosgw/s3/) |
| **Zenko (CloudServer)** | ✅ | ✅ | ✅ | [CloudServer](https://github.com/scality/cloudserver) |
| **Garage** | ✅ | ✅ | ⚠️ | [Compatibility Matrix](https://garagehq.deuxfleurs.fr/documentation/reference-manual/s3-compatibility/) |
| **SeaweedFS** | ✅ | ✅ | ⚠️ | [SeaweedFS S3 API](https://github.com/seaweedfs/seaweedfs/wiki/Amazon-S3-API) |
| **OpenStack Swift** | ✅ | ✅ | ⚠️ | [Swift S3 Compat](https://docs.openstack.org/swift/latest/s3_compat.html) |

### Cloud Services

| Provider | Tier 1 (Core) | Tier 2 (Reliability) | Tier 3 (Ecosystem) | Documentation |
| :--- | :---: | :---: | :---: | :--- |
| **AWS S3** | ✅ | ✅ | ✅ | [API Reference](https://aws.amazon.com/s3/) |
| **Wasabi** | ✅ | ✅ | ✅ | [API Support](https://wasabi.com/s3-compatible-cloud-storage/) |
| **Cloudflare R2** | ✅ | ✅ | ⚠️ | [S3 Compatibility](https://developers.cloudflare.com/r2/api/s3/api/) |
| **Backblaze B2** | ✅ | ✅ | ⚠️ | [S3 Compatible API](https://www.backblaze.com/docs/cloud-storage-s3-compatible-api) |
| **DigitalOcean Spaces** | ✅ | ✅ | ⚠️ | [Spaces API](https://docs.digitalocean.com/products/spaces/reference/s3-compatibility/) |
| **Scaleway Object Storage** | ✅ | ✅ | ⚠️ | [API Call List](https://www.scaleway.com/en/docs/object-storage/api-cli/using-api-call-list/) |
| **Google Cloud Storage** | ✅ | ✅ | ⚠️ | [Interoperability](https://cloud.google.com/storage/docs/interoperability) |
| **Linode (Akamai)** | ✅ | ✅ | ⚠️ | [Object Storage API](https://techdocs.akamai.com/cloud-computing/docs/object-storage-s3-api) |
| **IDrive e2** | ✅ | ✅ | ⚠️ | [Developer Guide](https://www.idrive.com/s3-storage-e2/guides/s3_developer_guide) |
| **Tigris** | ✅ | ✅ | ⚠️ | [S3 Compatibility](https://www.tigrisdata.com/docs/s3/) |
| **Oracle Cloud (OCI)** | ✅ | ✅ | ⚠️ | [S3 Compatibility API](https://docs.oracle.com/en-us/iaas/Content/Object/Tasks/s3compatibleapi.htm) |
| **IBM Cloud Object Storage** | ✅ | ✅ | ⚠️ | [Compatibility API](https://cloud.ibm.com/docs/cloud-object-storage?topic=cloud-object-storage-compatibility-api) |

