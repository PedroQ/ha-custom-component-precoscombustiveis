[![GitHub Release][releases-shield]][releases]
[![License][license-shield]](LICENSE.md)
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

# Preços dos Combustíveis - DGEG
Fuel Prices in Portugal - Custom Component for Home Assistant

# Installation
## HACS (Recommended)
This integration can be added to HACS as a custom (non-default) repository.

Assuming you have already installed and configured HACS, follow these steps:

1. Navigate to the HACS integrations page at http://<your-home-assistant>:8123/hacs/integrations.
2. Click the 3 vertical dots menu in the top right corner.
3. Choose 'Custom repositories'
4. Enter the name of this repository (https://github.com/netsoft-ruidias/ha-custom-component-precoscombustiveis/) in the text field in the dialog.
5. Choose 'Integration' from the Category list in the dialog.
6. Click 'Add'. The repository will now be added to your HACS.
7. Click the 'x' to close the dialog.
8. The integration is now visible. Click 'Install', and click 'Install' again.
9. Ready! Now continue with the configuration.

## Manual
(not recomended)

# Configuration

## Through the interface
1. Navigate to `Settings > Devices & Services` and then click `Add Integration`
2. Search for `Precos Combustiveis DGEG.PT integration`
3. (Go to [dgeg](https://precoscombustiveis.dgeg.gov.pt/api/PrecoComb/ListarDadosPostos), search for the desired post and copy the `Id`)
4. Enter the StationId 
5. Repeat the procedure as many times as desired to include other stations

# Legal notice
All product names, trademarks and registered trademarks in (the images in) this repository, are property of their respective owners. All images in this repository are used by the project for identification purposes only.