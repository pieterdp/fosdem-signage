
# FOSDEM Signage

* The _template_ folder contains all the source files for the internal and external signage.
* The _management_ folder contains all the source files and instructions for placement of the signs (internal and external).
* The year folders contain the generated PDF's.

## Overview

| Type | Purpose | Format | Dimensions | Location |
|------|---------|--------|------------|----------|
| *What's on today?* | Talks, stands, services | A1 | 594mm x 840mm | Entrance, staircase landing, lift landing |
| *Where do I find?* | Floor info, services, other buildings | A1 | 594mm x 840mm | Entrance, staircase landing, lift landing |


## Technical details

### Fonts and colours
* The official font is Frutiger. FOSDEM has a license to use it.
* The other fonts used are Source Sans Pro and Source Serif Pro (both open source fonts from Adobe).
* The purple is RGB R163 G35 B148.
* The grey is RGB R102 G102 B102.

### Software
* Most of the source files are in Scribus format.
* The source files for the arrows are in Adobe Illustrator format.
* Most image files are SVG or PNG.

### Formats
* Signs for the entrance are in A1 format.
* Internal signs are in A4 format.
* Arrows are a custom format.
* A4 signs should be laminated.
* Item height: 30mm

### Canvas size

| Page size | Canvas | Margins |
|-----------|--------|---------|
| A1 | 574mm x 820mm | 10mm |

### Style elements

| Element | Value | Notes |
|---------|-------|-------|
| Header font | Frutiger | *Requires FOSDEM license.* |
| Body font | Source Sans Pro | |
| Highlight colour | RGB `#a3238e` | *rgb(163, 35, 142)* |
| Grey colour | RGB `#666666` | *rgb(102, 102, 102)* |
