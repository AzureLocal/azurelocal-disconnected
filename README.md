# azurelocal-disconnected

azurelocal-disconnected is a repository in the AzureLocal organization, managed under the HCS platform standard.

---

## What this is

azurelocal-disconnected is a repository in the AzureLocal organization, managed under the HCS platform standard.

---

## Prerequisites

Before using this project, you need:

- PowerShell 7+ (`winget install Microsoft.PowerShell`)
- Azure CLI (`winget install Microsoft.AzureCLI`) — logged in as kris@hybridsolutions.cloud
- GitHub CLI (`winget install GitHub.cli`) — authenticated via `hcs-github-org-pat`
- {{Any other tools, runtimes, or SDKs this project requires}}

Load required environment variables before starting:

```powershell
. E:\git\platform\scripts\Load-HCSEnvironment.ps1
```

---

## Quick start

```powershell
# {{Step 1 — clone or navigate to the repo}}
cd E:\git\{{repo-name}}

# {{Step 2 — any setup steps}}

# {{Step 3 — the primary command to run or build}}
```

---

## Documentation

{{If a doc site exists, link it here. Otherwise link to key Markdown files.}}

| Doc | Description |
|---|---|
| [{{doc name}}](docs/{{file}}.md) | {{what it covers}} |

---

## Contributing

1. Create a feature branch: `git checkout -b feature/short-description`
2. Make changes following the [scripting](https://dev.azure.com/hybridcloudsolutions/Platform%20Engineering/_git/Platform%20Engineering?path=/docs/standards/scripting.md) and [documentation](https://dev.azure.com/hybridcloudsolutions/Platform%20Engineering/_git/Platform%20Engineering?path=/docs/standards/documentation.md) standards
3. Commit with `type(scope): description` format and link an ADO work item (`AB#<id>`)
4. Open a PR and link it to the ADO work item

---

## License

{{MIT / Proprietary — choose one and delete the other}}

MIT License — see [LICENSE](LICENSE)

*Proprietary — Hybrid Cloud Solutions LLC. All rights reserved.*

---

**Owner:** Kristopher Turner — kris@hybridsolutions.cloud
Hybrid Cloud Solutions LLC — hybridsolutions.cloud
