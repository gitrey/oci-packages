# oci-packages
OCI Packages

Build image
```bash
docker build -t ${AR_REGION}-docker.pkg.dev/${PROJECT_ID}/${AR_REPO_NAME}/test-configmap:v1 .
```

Push image
```bash
docker push ${AR_REGION}-docker.pkg.dev/${PROJECT_ID}/${AR_REPO_NAME}/test-configmap:v1
```