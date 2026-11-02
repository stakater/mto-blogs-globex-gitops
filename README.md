# mto-blogs-globex-gitops

The GitOps repository of tenant `globex`, for the tutorial
[Hands-on: tenants on OpenShift, carried into Argo CD](https://github.com/stakater/mto-blogs/tree/main/06-try-it-tenants-and-argocd).

- `hello.yaml`: a small web server with a Route. Its page says "Hello from
  tenant globex". In the tutorial, tenant `acme` tries to deploy it, and
  Argo CD refuses, because this is not acme's repository.
