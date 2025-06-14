The changelog is automatically generated and it follows [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format.

## [camunda-platform-10.7.1](https://github.com/camunda/camunda-platform-helm/releases/tag/camunda-platform-10.7.1) (2025-05-23)

### Fixes

- Description on chart.yaml for 8.5  (#3541)

<!-- generated by git-cliff -->
### Release Info

Supported versions:

- Camunda applications: [8.5](https://github.com/camunda/camunda/releases?q=tag%3A8.5&expanded=true)
- Camunda version matrix: [8.5](https://helm.camunda.io/camunda-platform/version-matrix/camunda-8.5)
- Helm values: [10.7.1](https://artifacthub.io/packages/helm/camunda/camunda-platform/10.7.1#parameters)
- Helm CLI: [3.17.3](https://github.com/helm/helm/releases/tag/v3.17.3)

Camunda images:

- docker.io/camunda/connectors-bundle:8.5.16
- docker.io/camunda/identity:8.5.16
- docker.io/camunda/operate:8.5.14
- docker.io/camunda/optimize:8.5.15
- docker.io/camunda/tasklist:8.5.16
- docker.io/camunda/zeebe:8.5.18
- registry.camunda.cloud/console/console-sm:8.5.116
- registry.camunda.cloud/web-modeler-ee/modeler-restapi:8.5.19
- registry.camunda.cloud/web-modeler-ee/modeler-webapp:8.5.19
- registry.camunda.cloud/web-modeler-ee/modeler-websockets:8.5.19

Non-Camunda images:

- docker.io/bitnami/elasticsearch:8.12.2
- docker.io/bitnami/keycloak:23.0.7
- docker.io/bitnami/os-shell:12-debian-12-r18
- docker.io/bitnami/postgresql:14.18.0-debian-12-r0
- docker.io/bitnami/postgresql:15.10.0-debian-12-r2

### Verification

To verify the integrity of the Helm chart using [Cosign](https://docs.sigstore.dev/signing/quickstart/):

```shell
cosign verify-blob camunda-platform-10.7.1.tgz \
  --bundle camunda-platform-10.7.1.cosign.bundle \
  --certificate-oidc-issuer "https://token.actions.githubusercontent.com" \
  --certificate-identity "https://github.com/camunda/camunda-platform-helm/.github/workflows/chart-release-chores.yml@refs/pull/3549/merge"
```
