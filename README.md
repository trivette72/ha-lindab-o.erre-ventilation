<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="custom_components/ambientika_ventilation/brand/dark_icon.png">
    <img src="custom_components/ambientika_ventilation/brand/icon.png" alt="Lindab Ventilation" width="256">
  </picture>
</p>

<h1 align="center">Lindab Ventilation for Home Assistant</h1>

<p align="center">
  Fork of a modern, independent Home Assistant integration for cloud-connected<br>
  Südwind Ambientika ventilation systems, with changed server to work with<br>
  Lindab and O.ERRE rebranded units.
</p>
<p align="center">
  Original integration: https://github.com/SoftwareSchmied/ha-ambientika-ventilation
</p>

<p align="center">
  Release: v0.1.0
</p>

Lindab and O.ERRE Ventilation discovers the supported devices on an O.ERRE
account and provides monitoring and safe controls without YAML.

> [!IMPORTANT]
> Version 0.1.0 is a public beta. It has been validated against the live cloud
> API and one Lindab DRJ-160 APP installation.

## Quick installation

### HACS

1. Add `"https://github.com/trivette72/ha-lindab-o.erre-ventilation"` under
   **HACS → Integrations → ⋮ → Custom repositories** as an **Integration**.
2. Install **Lindab and O.ERRE Ventilation** and restart Home Assistant.
3. Open **Settings → Devices & services → Add integration** and select
   **Lindab and O.ERRE Ventilation**.

### Manual

For more information, key features, supported devices, entities, reliability and cloud usage, diagnostics and privacy, troubleshooting and requirements follow original integration. Instead of using Ambientika account, download the official O.ERRE application called O.Tech, create an O.ERRE account, register your ventilation units, and try adding them to Home Assistant using this fork.

Given the experimental nature of this fork, all functionality is used at your own risk.

### Development
The project is licensed under the MIT License and is not affiliated with or
endorsed by Lindab or O.ERRE. Lindab or O.ERRE are trademarks of their
respective owner.
