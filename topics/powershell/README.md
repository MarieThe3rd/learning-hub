# 💙 PowerShell

Master PowerShell scripting, automation, and DevOps tooling in the Microsoft ecosystem.

## 🎯 Learning Goals

- [ ] Write effective PowerShell scripts using the pipeline idiom
- [ ] Create reusable functions with proper parameter validation and help docs
- [ ] Handle errors gracefully with try/catch and error action preferences
- [ ] Automate file system, process, and service management tasks
- [ ] Use the Az PowerShell module to manage Azure resources
- [ ] Integrate PowerShell scripts into GitHub Actions CI/CD pipelines
- [ ] Test PowerShell scripts with the Pester testing framework
- [ ] Use PowerShell Core (pwsh) cross-platform

## 🗺️ Learning Path

### Stage 1: PowerShell Fundamentals
- Cmdlets, aliases, and the pipeline
- Variables, arrays, and hashtables
- Control flow: `if`, `foreach`, `while`, `switch`
- Working with strings, numbers, and dates
- Getting help: `Get-Help`, `Get-Member`, `Get-Command`

### Stage 2: Functions & Modules
- Writing functions with `param()` blocks
- Parameter validation attributes (`[ValidateNotNullOrEmpty()]`, etc.)
- Comment-based help (`<# .SYNOPSIS ... #>`)
- Script modules (`.psm1`) and module manifests (`.psd1`)
- Dot-sourcing vs. importing modules

### Stage 3: Error Handling & Debugging
- Terminating vs. non-terminating errors
- `$ErrorActionPreference` and `-ErrorAction`
- `try / catch / finally` blocks
- Writing to error, warning, and verbose streams
- Debugging with `Set-PSBreakpoint` and VS Code debugger

### Stage 4: Automation & System Management
- File and folder operations (`Get-ChildItem`, `Copy-Item`, etc.)
- Managing Windows services and processes
- Scheduled tasks via PowerShell
- Registry operations
- Remote management with `Invoke-Command` and PS Remoting

### Stage 5: Azure & DevOps Automation
- Installing and using the Az PowerShell module
- Authenticating to Azure (service principals, managed identities)
- Automating Azure resource management
- PowerShell in GitHub Actions (`shell: pwsh`)
- Testing scripts with Pester

## 📁 Folder Structure

```
topics/powershell/
├── notes/       ← Add your markdown notes here
├── exercises/   ← PowerShell scripts and automation practice
└── README.md    ← This file
```

## 🔗 Related Topics

- **Azure Development** — Azure CLI and Az module for cloud automation
- **Dev Principles & Practices** — Applying Clean Code and structure to scripts

## 🤖 Mentor

Use the `@powershell-mentor` prompt for PowerShell-specific guidance, or `@mentor` with `topic = "PowerShell"`.
