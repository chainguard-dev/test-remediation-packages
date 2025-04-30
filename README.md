This is a Wolfi packages repository for testing our CVE remediation service

Each directory contains a list of files which are required to build the listed APKs and a README file with
information on how to fix its detected CVEs for these APKs.


To fix these CVEs, we have used the following CLI:

```bash
Usage:
  ai-cve-remediation [flags]
  ai-cve-remediation [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  help        Help about any command
  version     Prints the version

Flags:
      --arch string                     chosen architecture for the package (default "aarch64")
      --build-package                   build the Wolfi package
      --dir string                      optional override to the local directory that contains the package.  Defaults to cloning Wolfi os packages repo into a temp folder
      --dry-run                         print the Wolfi package definition
      --gcs-scan-bucket-name string     GCS Scan Bucket name (default "grype-scan-results-wxavnszrsjp4")
      --github-organization string      git organization to package repository for Wolfi images (default "hectorj2f")
      --github-repository string        git repository to package repository for Wolfi images (default "os")
      --github-user-email string        github user email to create the pull request (default "hector@chainguard.dev")
      --github-username string          github username to create the pull request (default "hectorj2f")
  -h, --help                            help for ai-cve-remediation
      --image-ref string                image reference with the affected vulnerability (default "chainreg.biz/chainguard-private/vitess-lite@sha256:9048831be5854c4f741b6ac9dd1484a1d69920b11869ad4f82948867f6e3192f")
      --package-name string             Package name (default "vitess-20.0")
      --package-repo-ref string         Package repository branch name (default "main")
      --vuln-component-name string      vulnerability component name
      --vuln-component-version string   vulnerability component version
      --vuln-fixed-version string       vulnerability component fixed version
      --vuln-id string                  CVE-ID (default "GHSA-mwcw-c2x4-8c55")
      --vuln-type string                Component type affected by the vulnerability (e.g. java-archive, rust-crate, npm, gem, go-module, python (default "npm")

Use "ai-cve-remediation [command] --help" for more information about a command.
```

## Run

```bash
./ai-cve-remediation --build-package=true --vuln-id=GHSA-gmj6-6f8f-6699 --vuln-type=python --image-ref=cgr.dev/chainguard-private/kubeflow-volumes-web-app@sha256:f9e189a0e2975d0829458409b510c15f858387b0cc2927b840ae251ea5cdec4f --github-repository=os --package-name=kubeflow-volumes-web-app
```
