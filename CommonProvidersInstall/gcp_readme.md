<PROJECT_ID> in gcp_config.yaml must match from key [https://cloud.google.com/iam/docs/creating-managing-service-account-keys](https://cloud.google.com/iam/docs/creating-managing-service-account-keys)

### Create secret:
`kubectl create secret generic gcp-secret -n upbound-system --from-file=creds=./gcp-credentials.json`