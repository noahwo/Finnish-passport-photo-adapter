# Finnish Passport Photo Adapter

Straighten, scale, and crop portraits to meet Finnish passport photo
requirements in [Poliisin passikuvaohje](https://poliisi.fi/documents/25235045/31329600/Poliisin-passikuvaohje-2020-FI.pdf/d7709348-8248-09a0-8b74-7526e6ee2a5d?t=1600339651285), then arrange them on a printable photo sheet.

## Requirements

The app only needs a modern web browser. No install or build step is required.

## Quick Start

Open `passportgen.html` in a browser.

## How To Use

1. Choose **Open Photo** in slot A.
2. Click the center of one eye, then the center of the other eye.
3. Click the crown of the head, excluding hair.
4. Click the bottom of the chin.
5. Adjust brightness or contrast if needed.
6. Download the active passport photo, or use **Print Layout** to create a photo
   sheet.

Photo B can be prepared the same way. When both slots are ready, the print sheet
alternates photos A and B.

## Output

- Finnish passport photo size: 36 x 47 mm.
- Official export: 500 x 653 px JPEG, compressed to stay under 250 KB when
  possible.
- Original export: JPEG using the source crop resolution, without the official
  pixel or file-size limits.
- Print sheets: 300 DPI JPEG layouts for 9 x 13 cm, 10 x 15 cm, 13 x 18 cm, or a
  single-photo sheet.

## Print Sheet Name

The print-sheet download name can be edited in the **Name** field. By default it
uses:

`Finnish passport photo to print YYYY-MM-DD HH.MM.jpg`

The app adds a `.jpg` extension if needed.

## Autosave

The current workflow, selected paper size, export mode, adjustments, and print
sheet name are saved in browser local storage and restored on reload when
possible.
