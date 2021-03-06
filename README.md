# Sketchup 2 GTA

Exports [Sketchup](https://www.sketchup.com/download) models to Grand Theft Auto IV / V.

Supported formats:
- GTA: IV
  - ODR/ODD (OpenIV)
  - OBN/OBD (OpenIV)
  - OTD (OpenIV)
  - WPL
  - IDE
- GTA: V
  - ODR (OpenIV)
  - OTD (OpenIV)

## Setup

Installing the plugin is easy, just follow these simple steps:
1. Download the [latest version](https://github.com/ShadwLink/Sketchup2IV/releases) of the plugin.
2. Open Sketchup
3. Open the Sketchup extension manager (Window -> Extension manager)
4. Click the `Install extension` button and select the `rbz` package

That's it!

## Usage
##### Version export format
To change the export format, you need to open the Extension menu, GTA Version and select one of the versions. By default GTA IV is selected.

##### Export
Models can be exported by converting them to components. Simply select the component, right click and select GTA Export.

## Tutorial
A step by step guide that exports a tutorial scene to GTA can be found on my [website](https://shadow-link.nl/projects/sketchup-iv-exporter/).

## Version history

##### 0.5.0
- Initial support for V formats
  - ODR
  - OTD

##### 0.4.2
- Use relative file path for OTD export

##### 0.4.1
- Fixed OpenFormats version in mesh files
- Select export path for WPL files
- Select export path for IDE files
- Filter duplicates on IDE export
- Fix UV coordinates

##### 0.4.0
- Added OTD support

##### 0.3.0
- Added ODD and OBN support

##### 0.2.0
- Sketchup 2017 support

##### 0.1.0
- Initial release
- Export ODR
- Export OBD
- Export WPL
- Export IDE

## Author
Shadow-Link

![Shadow-Link logo](src/shadowlink_iv_exporter/help/sl_icon.png)