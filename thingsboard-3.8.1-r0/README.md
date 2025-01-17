---
# README for command 11
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-rhx6-c78j-4q9w"
vuln-type: "npm"
image-ref: "cgr.dev/chainguard-private/thingsboard-tb-web-ui@sha256:2783757fd95872fc728d368797348e3972316bd12b5e391b96702bbc956cbd63"
github-repository: "os"
package-name: "thingsboard"
vuln-component-name: "path-to-regexp"