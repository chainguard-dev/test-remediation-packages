# README for command 15
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-rhx6-c78j-4q9w"
vuln-type: "npm"
image-ref: "cgr.dev/chainguard-private/tileserver-gl@sha256:419d523bf8c53136c5c3a31a7c5a95134d19425409238cb353fab0db0402ed38"
github-repository: "os"
package-name: "tileserver-gl"
vuln-component-name: "path-to-regexp"

---
# README for command 16
command:
name: "ai-cve-remediation"
description: "The Wolfi CVE remediation tool"
parameters:
build-package: true
vuln-id: "GHSA-3xgq-45jj-v275"
vuln-type: "npm"
image-ref: "cgr.dev/chainguard-private/tileserver-gl@sha256:2705b767f976b43f29da631901101a46262a458b7a1b14ce464611c3f97f832c"
github-repository: "os"
package-name: "tileserver-gl"
vuln-component-name: "cross-spawn"