---
title: "Get-Help"
params:
    bookToC: false
---

# Get-Help

Use to well... Get help for other parts of PowerShell.

## Usage

```powershell
Get-Help "<Cmdlet-Name>"
```

## Useful Parameters

| Parameter | Description |
| :--- | :--- |
| `-Examples` | Provides examples of how to use the cmdlet you are seeking help with. |

## Notes

- To get the most out of this cmdlet you can use the [`Update-Help`](Update-Help.md) cmdlet to download updated help files.
  - As an example, the `-Examples` parameter won't work until `Update-Help` is run.

## See Also

- [Microsoft Docs: Get-Help](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/get-help)
