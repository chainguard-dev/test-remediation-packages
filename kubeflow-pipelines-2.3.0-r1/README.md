# README for command 12
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-rhx6-c78j-4q9w"
vuln-type: "npm"
image-ref: "cgr.dev/chainguard-private/kubeflow-pipelines-frontend@sha256:eb05e3c794ba8bed976b8d251dcdfd7159a8c58ec986381e84134c468fa09b8a"
github-repository: "os"
package-name: "kubeflow-pipelines"
vuln-component-name: "path-to-regexp"
