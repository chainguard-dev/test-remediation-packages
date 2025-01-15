# README for command 8
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-r9px-m959-cxf4"
vuln-type: "go-module"
image-ref: "cgr.dev/chainguard-private/argocd-image-updater@sha256:d367725ede0c1f8bac65e2fa770c0e901ead05772fda9ad32d70a37d209a90ad"
github-repository: "os"
package-name: "argocd-image-updater"