# PyPNMApps — DOCSIS PNM Tools and Applications

Open-source tools for DOCSIS proactive network maintenance, from Python APIs and
CMTS workflows to desktop and web-based analysis.

## Projects

<table>
  <tr>
    <td width="300" align="center">
      <a href="https://github.com/PyPNMApps/PyPNM">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PyPNMApps/PyPNM/8e6cdc9933676a74bc1d211dde11f3841d0b2369/docs/images/logo/pypnm-dark-mode-hp.png">
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PyPNMApps/PyPNM/8e6cdc9933676a74bc1d211dde11f3841d0b2369/docs/images/logo/pypnm-light-mode-hp.png">
          <img src="https://raw.githubusercontent.com/PyPNMApps/PyPNM/8e6cdc9933676a74bc1d211dde11f3841d0b2369/docs/images/logo/pypnm-light-mode-hp.png" alt="PyPNM logo" width="280">
        </picture>
      </a>
    </td>
    <td>
      <h3><a href="https://github.com/PyPNMApps/PyPNM">PyPNM</a></h3>
      <p>Python library and REST API for DOCSIS modem health, diagnostics, and proactive network maintenance analysis.</p>
    </td>
  </tr>
  <tr>
    <td width="300" align="center">
      <a href="https://github.com/PyPNMApps/PyPNM-CMTS">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PyPNMApps/PyPNM-CMTS/main/docs/images/pypnm-cmts-hp-dark-43.png">
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PyPNMApps/PyPNM-CMTS/main/docs/images/pypnm-cmts-hp-light-43.png">
          <img src="https://raw.githubusercontent.com/PyPNMApps/PyPNM-CMTS/main/docs/images/pypnm-cmts-hp-light-43.png" alt="PyPNM-CMTS logo" width="280">
        </picture>
      </a>
    </td>
    <td>
      <h3><a href="https://github.com/PyPNMApps/PyPNM-CMTS">PyPNM-CMTS</a></h3>
      <p>CMTS-focused automation, validation, and operational workflows built on PyPNM.</p>
      <p><em>Under development.</em></p>
    </td>
  </tr>
  <tr>
    <td width="300" align="center">
      <a href="https://github.com/PyPNMApps/PyPNM-CMTS-WebUI">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PyPNMApps/PyPNM-CMTS-WebUI/main/docs/images/PyPNM-WebUI-dark.png">
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PyPNMApps/PyPNM-CMTS-WebUI/main/docs/images/PyPNM-WebUI-light.png">
          <img src="https://raw.githubusercontent.com/PyPNMApps/PyPNM-CMTS-WebUI/main/docs/images/PyPNM-WebUI-light.png" alt="PyPNM-CMTS-WebUI logo" width="280">
        </picture>
      </a>
    </td>
    <td>
      <h3><a href="https://github.com/PyPNMApps/PyPNM-CMTS-WebUI">PyPNM-CMTS-WebUI</a></h3>
      <p>Web client for CMTS-facing REST APIs, with shared capture and analysis views and a PyPNM compatibility profile.</p>
    </td>
  </tr>
  <tr>
    <td width="300" align="center">
      <a href="https://github.com/PyPNMApps/PyPNM-PMA">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PyPNMApps/PyPNM-PMA/main/docs/images/PyPNM-PMA-dark-mode-hp.png">
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PyPNMApps/PyPNM-PMA/main/docs/images/PyPNM-PMA-light-mode-hp.png">
          <img src="https://raw.githubusercontent.com/PyPNMApps/PyPNM-PMA/main/docs/images/PyPNM-PMA-light-mode-hp.png" alt="PyPNM-PMA logo" width="280">
        </picture>
      </a>
    </td>
    <td>
      <h3><a href="https://github.com/PyPNMApps/PyPNM-PMA">PyPNM-PMA</a></h3>
      <p>Design and evaluate OFDM/OFDMA profiles using RxMER, simulated impairments, and repeatable what-if analysis.</p>
      <p><em>Under development.</em></p>
    </td>
  </tr>
  <tr>
    <td width="300" align="center">
      <a href="https://github.com/PyPNMApps/PNM-Viewer-Toolkit">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PyPNMApps/PNM-Viewer-Toolkit/master/docs/images/pnm-viewer-toolkit-logo-dark.svg">
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PyPNMApps/PNM-Viewer-Toolkit/master/docs/images/pnm-viewer-toolkit-logo-light.svg">
          <img src="https://raw.githubusercontent.com/PyPNMApps/PNM-Viewer-Toolkit/master/docs/images/pnm-viewer-toolkit-logo-light.svg" alt="PNM Viewer Toolkit logo" width="280">
        </picture>
      </a>
    </td>
    <td>
      <h3><a href="https://github.com/PyPNMApps/PNM-Viewer-Toolkit">PNM Viewer Toolkit</a></h3>
      <p>Native Qt desktop viewer and Rust-powered <code>pnm-decode</code> CLI. Open local DOCSIS PNM captures, explore measurement graphs, and export JSON.</p>
      <p><em>Under development.</em></p>
    </td>
  </tr>
</table>

## Supporting tools

- [Postman API collections](https://github.com/PyPNMApps/Postman-PyPNMApps-API) —
  request collections, environments, and visualizers for PyPNM and PyPNM-CMTS.
- [Common development tools](https://github.com/PyPNMApps/PyPNM-Common-Development) —
  shared Git, release, and security/hygiene tooling.
- [PyPNM-WebUI compatibility wrapper](https://github.com/PyPNMApps/PyPNM-WebUI) —
  installation and migration entrypoints for the unified
  [PyPNM-CMTS-WebUI](https://github.com/PyPNMApps/PyPNM-CMTS-WebUI).
