# Helmfile Deps Kustomization issue

1. Execute `helmfile deps` using helmfile version `0.161.0`.

   Verify that it is trying to update the temporary chart for the provided kustomization.

2. Execute `helmfile deps` using helmfile version `0.162.0`.

   Observe the error message and the path that was used when executing the `helm upgrade` command.

