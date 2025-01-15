# README for command 6
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-q2x7-8rv6-6q7h"
vuln-type: "python"
image-ref: "cgr.dev/chainguard-private/mlflow-bitnami@sha256:596b27d96288d412eac66fba467895f2992a724a85a79219703716c0f491c469"
github-repository: "os"
package-name: "mlflow"
vuln-component-name: "Jinja2"
dry-run: true
vuln-fixed-version: "3.1.5"
vuln-component-version: "3.1.4"