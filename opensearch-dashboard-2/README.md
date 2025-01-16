```yaml
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-3xgq-45jj-v275"
vuln-type: "npm"
image-ref: "cgr.dev/chainguard-private/opensearch-dashboards@sha256:a7fe5ce2a7b7c225d0398d78334886b2e8a691299d0a3f92b51e879da1c403e5"
github-repository: "os"
package-name: "opensearch-dashboards-2"
vuln-component-name: "cross-spawn"
```