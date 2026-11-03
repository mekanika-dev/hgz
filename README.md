# Z350 & Z600 Upgrade

This repository covers the two Z-axis height upgrades for Mekanika machines:

- **Z350** (formerly *High-Z*) - available for Evo, Pro and Fab
- **Z600** (*Super High-Z*) - available for Pro and Fab

- [Assembly Guide & Documentation](https://support.mekanika.io/products/high-z-upgrade)
- [Shop](https://www.mekanika.io/en/store/be/high-z)
- [Contact](https://www.mekanika.io/contact-us/)

![Z350](https://www.mekanika.io/_next/image?url=https%3A%2F%2Fs3storage-medusa.ams3.digitaloceanspaces.com%2FHigh-Z%20-%20Pro%20-%20Studio-01JKTTH39QC2VKCSV07H2V23QM.jpg&w=1080&q=90)

## Repository Structure

- **`bom/`** - Bill of Materials
- **`cad/`** - CAD files

The Bill of Materials is available as one CSV file per configuration (Z350-Evo, Z350-Pro_Fab, Z600-Fab, Z600-Pro), which is dynamically updated from our ERP. We recommend using this **[web viewer](https://mekanika-dev.github.io/data-sync-actions/odoo/bom-viewer.html)** to browse its content.

All 3D assembly files are made in STEP format and compatible with many CAD software. Please note that you will need Git LFS installed to clone or pull the repo correctly, since these files exceed 100MB.

The design files can also be viewed in web browsers using these links:

- [Z350 - Evo config](https://a360.co/45Vu9HG)
- [Z350 - Pro/Fab config](https://a360.co/3VkAMhR)

## Assembly Guide

The assembly guide is available on our [support website](https://support.mekanika.io/products/high-z-upgrade). If you have feedback or want to raise an issue about a specific assembly step, you can use the feedback buttons available on each step's page.

## Community

Mekanika encourages collaborative design and innovation. We welcome:

- Designers and engineers to contribute
- Feedback on design variations
- Any discussions around or products and potential improvements

Don't hesitate to join us on our [Discord](https://discord.gg/n7RsBtUdGc)

## License

This project is licensed under the **CERN Open Hardware Licence Version 2 - Strongly Reciprocal** ([CERN-OHL-S v2](https://ohwr.org/cern_ohl_s_v2.pdf))

For the complete license terms, see REUSE.toml
