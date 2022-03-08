![image](https://user-images.githubusercontent.com/49169467/157120168-1e01c50c-2c67-4652-a036-edb9a9f4fff6.png)
https://www.atlassian.com/blog/git/written-unwritten-guide-pull-requests

# Initial process development.

1. Create Github code repository, base on `template` repository. Must be Lisa's workflow name, in lower case with dash (replacing spaces);
2. Create ECR. Must be Lisa's workflow name, in lower case with dash (replacing spaces);
3. Replace inside `.github/workflows/build_image_push_to_ecr_and_eks.yaml`, the `XXXXXXXXXXXXXXXXXXXX` with the same ECR name;
4. Create a branch for development, starting from `production` branch;
5. [optional] If the process needs a database schema inside dbRobots, pleas ask Diogo or Marcelo. (Create schema, and users);
6. Code!
7. Create a PR to `staging`, and merge it to deploy to EKS staging namespace;
8. Create a PR to `production`, and merge it to deploy to EKS production namespace;


# DDL and UPDATE etc...


```
Repositories README kinds
 - RPA (Robotic Process
 - Web - Backend 
 - Web - UI
 - Mobile development (UI)
 - BI / Reports (??????)
 - ETL (
 - Outros?
```


Ecommerce
 - Grab source code to our Organization
 - Configure deployment automation

Orchestrator
 - Configure deployment automation

