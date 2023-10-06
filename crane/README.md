# oci-packages
OCI Packages

Install crane - https://github.com/google/go-containerregistry/tree/main/cmd/crane


Archive config file
```bash
tar -cf test-namespace.tar test-namespace.yaml
```

Append to remote image
```bash
./crane append -f test-namespace.tar -t ${AR_REGION}-docker.pkg.dev/${PROJECT_ID}/${AR_REPO_NAME}/test-namespace:v1
```

