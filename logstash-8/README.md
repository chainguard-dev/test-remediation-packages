# README for command 2
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-hxx2-7vcw-mqr3"
vuln-type: "gem"
image-ref: "cgr.dev/chainguard-private/logstash-bitnami@sha256:21631e2dd7ffdddf950f7313030566294f1e782af88cba57c37cbccfa57c02ac"
github-repository: "os"
package-name: "logstash-8"