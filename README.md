Docker Registry with IDCF Object Storage
========================================

idcf-registry is a Docker Registry image with IDCF Object Storage.

# Usage
```bash
docker run --name registry \
  -p 5000:5000 \
  -e "REGISTRY_BUCKET=${YOUR_BUCKET}" \
  -e "AWS_ACCESS_KEY_ID=${YOUR_ACCESS_KEY}" \
  -e "AWS_SECRET_ACCESS_KEY=${YOUR_SECRET_KEY}" \
  idcf-registry
```
