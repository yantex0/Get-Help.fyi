---
title: "Show-Command"
tags: ["cmdlet"]
description: "Use this cmdlet to find other cmdlets, easily run cmdlets with their parameters or create a semi-custom GUI for your own function."
weight: 0
---

# Show-Command

> [!NOTE]
> I wish this one of the first cmdlets I ever learnt years ago! Run `Show-Command` and see what it can do for you! This is a cmdlet for all skill levels, it is a cmdlet you will certainly get value from.

## Different Uses

* **Basic Uses:** This cmdlet allows for finding other cmdlets very easily.
* **Intermediate:** You can use it with native cmdlets to construct and run with their parameters.
* **Advanced:** Use the `Show-Command` GUI for your own scripts to allow easy input of values at runtime.

## Usage

```powershell
Show-Command
```

## Notes

* also allows for creating an interface for other users (or yourself) to run custom scripts you have made.
* The interface is the same as the 'Show Command Add-On' from PowerShell ISE.
* It is like a combination of [`Get-Help`](..\cmdlets\get-help.md) and [`Get-Command`](..\cmdlets\get-command.md) but within a simple interface.

## See Also

* [Microsoft Docs: Show-Command](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/show-command)
