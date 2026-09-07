# Mgecomp

VB6 Manage Computers utility (`MgeComp.exe`) that lists domain computers and shows per-machine status (up/down via ping/IP, WMI `Win32_ComputerSystem` DomainRole) with config from `Mgecomp.ini` and an audit trail. Open `Mgecomp.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `MgeComp` (`Mgecomp.vbp`) | VB6 | WinForms exe | MgeComp |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Mgecomp.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSCOMCTL.OCX`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Mgecomp`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
