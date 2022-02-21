# Initial process development.

1. Create Github code repository, base on `template` repository. Must be Lisa's workflow name, in lower case with dash (replacing spaces);
2. Create ECR. Must be Lisa's workflow name, in lower case with dash (replacing spaces);
3. Replace inside `.github/workflows/build_image_push_to_ecr_and_eks.yaml`, the `XXXXXXXXXXXXXXXXXXXX` with the same ECR name;
4. Create a branch for development, starting from `production` branch;
5. Code!
6. Create a PR to `staging`, and merge it to deploy to EKS staging namespace;
7. Create a PR to `production`, and merge it to deploy to EKS production namespace;
