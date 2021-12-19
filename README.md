# What is this
- This is sample code of nvml and datadog agent setting manifest and Dockerfile
  - Use IRSA + ASCP to make setting secure
    - IRSA: https://docs.aws.amazon.com/eks/latest/userguide/iam-roles-for-service-accounts.html
    - ASCP: https://docs.aws.amazon.com/secretsmanager/latest/userguide/integrating_csi_driver.html
# Why create this
- [Officail Document](https://docs.datadoghq.com/integrations/nvml/) is not enough to set up, so I want to provide some example codes to those who will try to set up nvml for datadog with k8s

