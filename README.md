![Oracle APEX](https://img.shields.io/badge/Oracle%20APEX-Compatible-red) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow) ![License: MIT](https://img.shields.io/badge/License-MIT-green)

A production-ready Oracle APEX plug-in that transforms any image region into a professional, interactive photo viewer.

## Table of Contents
- [Preview](#Preview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Attribute Reference](#attribute-reference)
- [Download](#download)
- [About the Author](#about-the-author)
- [License](#license)

## Preview
<!-- GIF Preview will be added here -->
<img width="436" height="428" alt="image" src="https://github.com/user-attachments/assets/1ba1d3bd-46ff-4910-ac20-8b67f0f34ae2" />
<img width="785" height="383" alt="image" src="https://github.com/user-attachments/assets/de4cdfc1-1a2a-4195-81f6-0c74a12ecca3" />
![apex_zoom_plugin](https://github.com/user-attachments/assets/262201eb-aca8-42a9-9aac-b0dafe4c1c8b)



## Features
- Coordinate-aware zooming toward the mouse cursor position (like Google Maps)
- Linear zoom sensitivity via scroll wheel, smooth and predictable
- Pan and drag support after zooming in
- Double-click to reset to original position and 1x scale
- Native browser Fullscreen API for full monitor takeover
- Contextual cursor (zoom-in at 1x scale, grab cursor when zoomed)
- Scale lock that prevents zooming out below original image size
- Automatic CSS safety injection (overflow hidden, position relative) to protect APEX page layout
- Two developer-facing attributes in APEX Page Designer: Attribute 1 for Zoom Speed, Attribute 2 for Fullscreen Toggle
- Works perfectly with BLOB images without extra server calls
- Compatible with Oracle APEX Universal Theme
- Built with JavaScript ES6, PL/SQL Render Function, HTML5 MouseWheel API, and HTML5 Fullscreen API

## Requirements
- Oracle APEX 19.2 or above
- Modern browser with HTML5 support

## Installation
1. Go to the Releases tab and download the latest .sql file
2. In your APEX application open Shared Components then Plug-ins then Import
3. Upload the downloaded .sql file
4. Go to your page and apply a Dynamic Action to your image region using this plug-in

## Attribute Reference
| Attribute | Name | Description |
|---|---|---|
| Attribute 1 | Zoom Speed | Controls how fast the image zooms on scroll. Default is 0.1 |
| Attribute 2 | Fullscreen Toggle | Show or hide the fullscreen button on the image |

## Download
<!-- Plugin .sql file will be uploaded to the Releases section -->
Visit the [Releases](../../releases) tab to download the latest version of the plug-in.

## About the Author
Hassan Raza is an Oracle ACE Apprentice at SH Software Solution, Pakistan.

## License
MIT
