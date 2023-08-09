# renovatebot-helm-oci
Minimal reproduction repo for helm oci bug

Current behavior is that the dependency lookup fails:

```
⚠ Dependency Lookup Warnings ⚠
Renovate failed to look up the following dependencies: Failed to look up helm package karpenter.
Files affected: kustomization.yaml
```

Expected behavior is that it should suggest upgrading.
