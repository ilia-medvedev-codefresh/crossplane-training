Tasks:

Preparation:
- Deploy cluster with Crossplane and Helm provider. Create default provider config for Helm.

Basic:
1. Create a simple Helm release with Crossplane that deploys vcluster to a namespace on K3D cluster
2. Create a ProviderConfig that will enable Helm provider to deploy to the vcluster created above.
3. Deploy ArgoCD to the vcluster using ArgoCD Helm chart using crossplane

composition:
3. Wrap the same thing in a composition
4. Try to deploy something into vcluster using the same composition.