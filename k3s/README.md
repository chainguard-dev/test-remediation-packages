# README for command 3
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-w32m-9786-jp63"
vuln-type: "go-module"
image-ref: "cgr.dev/chainguard-private/k3s-static@sha256:e74f7dfe584d38577ee339e442af02445d11ce19182f249fca5bafb8595bacbf"
github-repository: "os"
package-name: "k3s"