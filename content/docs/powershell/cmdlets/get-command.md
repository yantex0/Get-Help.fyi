---
title: "Get-Command"
tags: ["cmdlet"]
description: "Used to find commands if you know ANYTHING about it."
---

# Get-Command

**Note:** This used to be my go-to cmdlet to find cmdlets but since learning about [Show-Command](show-command.md) I just use  that, much easier.

Used to find commands if you know ANYTHING about it.

Are you looking to find info about a file or process or anything? This likely will be a 'Get' cmdlet. Use `Get-Command -Verb Get`
Are you looking to work with files or folders (which PowerShell calls "Items")? Use `Get-Command -Noun *Item*`

The `*` acts as a wildcard, meaning it will find any cmdlet where the noun contains "Item" (such as `Get-Item`, `Get-ChildItem`, or `Get-ItemProperty`).

**Aliases:** `gc`

## Usage

```powershell
Get-Command "<Cmdlet-Name>"
```

## Useful Parameters

| Parameter | Description |
| :--- | :--- |
| `-Noun` | To specify a noun to search for. |
| `-Verb` | To specify a verb to search for. |

## Notes

- Any additional notes about the cmdlet.

## See Also

- [Microsoft Docs: Get-Command](https://learn.microsoft.com/)
