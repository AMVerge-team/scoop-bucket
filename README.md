<p align="center">
  <img src="assets/AMVerge-Scoop.gif" alt="AMVerge Scoop" width="1440"/>
</p>

# AMVerge Scoop Bucket

**Official Scoop bucket for installing AMVerge on Windows (64-bit).**  
Install, upgrade, and manage AMVerge directly from your terminal using Scoop.

---

## Available Manifests

| Manifest | Description | Architecture | Requirements |
| :--- | :--- | :--- | :--- |
| `amverge` | Fast desktop scene-splitting, semantic scene search, and clip-export software | 64-bit (`x64`) | Windows 10 / 11 |

---

## Installation

Add the bucket and install AMVerge:

```powershell
scoop bucket add amverge https://github.com/AMVerge-team/scoop-bucket
scoop install amverge
```

Or install directly from the manifest URL in a single command:

```powershell
scoop install https://raw.githubusercontent.com/AMVerge-team/scoop-bucket/main/bucket/amverge.json
```

---

## Usage

| Action | Command |
| :--- | :--- |
| **Add Bucket** | `scoop bucket add amverge https://github.com/AMVerge-team/scoop-bucket` |
| **Install** | `scoop install amverge` |
| **Update** | `scoop update amverge` |
| **Uninstall** | `scoop uninstall amverge` |

AMVerge also includes a built-in auto-updater, and this bucket runs an automated check every 6 hours to stay in sync with GitHub releases.

---

## Repository Structure

```txt
scoop-bucket/
├── .github/
│   └── workflows/
│       └── excavator.yml   # Automated manifest version & hash updater
├── assets/
│   └── AMVerge-Scoop.gif   # Animated RGB banner
├── bucket/
│   └── amverge.json        # Scoop manifest for AMVerge
└── README.md
```

---

## Links

- **Website**: [amverge.app](https://amverge.app/)
- **Desktop App**: [AMVerge-team/AMVerge](https://github.com/AMVerge-team/AMVerge)
- **CLI Backend**: [AMVerge-team/AMVerge-CLI](https://github.com/AMVerge-team/AMVerge-CLI)
- **After Effects Extension**: [AMVerge-team/AMVerge-Extension](https://github.com/AMVerge-team/AMVerge-Extension)
- **Discord**: [Join the AMVerge Discord](https://discord.gg/bmXjTgsAaN)
