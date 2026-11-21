---
title: "PowerShell"
weight: 2
params:
  bookFlatSection: true
---

# PowerShell

---

**PowerShell is awesome. It can do so much, it is (mostly) intuitive, its functional, its fun.**

## Guide Info

---

1. All guides are using **Windows 11**.
1. All guides are using [PowerShell 7.7+][ps-core] unless stated otherwise. For clarity, I will refer to these editions as:

    | Edition            | Characteristics                             | Link                                     |
    | ------------------ | ------------------------------------------- | ---------------------------------------- |
    | PowerShell         | Newer, actively maintained, cross platform. | [PowerShell][ps-core]                    |
    | Windows PowerShell | Older, deprecated, Windows only.            | [Windows PowerShell][Windows-PowerShell] |

1. All guides are using [Windows Terminal](https://learn.microsoft.com/en-us/windows/terminal/).

## Setup

---

### Installing PowerShell

The easiest way to install PowerShell is by downloading the latest release from the official Github repo:
<https://github.com/PowerShell/PowerShell/releases/latest>

Download the **.msixbundle** file from the releases page. Once downloaded, run the .msixbundle file to install PowerShell.

### Windows Terminal Setup

To set **Windows Terminal** as your default terminal application and set PowerShell as default within it:

1. Open **Windows Terminal**.
1. Press **`Ctrl+,`** to open the settings menu.
1. On **Startup** tab (initial tab to open):
    1. Change **Default profile** to 'PowerShell'.
    1. Change **Default terminal application** to 'Windows Terminal'.

**Optional** (Lets personalise your terminal!):

1. On **Profiles** tab:
    1. Click **Color schemes**
    1. Click on a colour scheme you like (I am partial to Solarized Dark, why not choose that? 😉)
    1. Click 'Set as default' button to apply to all profiles.

<!-- Referenes: -->
[ps-core]: https://learn.microsoft.com/en-au/powershell/scripting/overview?view=powershell-7.6
[Windows-PowerShell]: https://learn.microsoft.com/en-us/powershell/scripting/what-is-windows-powershell?view=powershell-5.1
