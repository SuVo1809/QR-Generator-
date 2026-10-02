# OmniCode Studio ⚡

A lightweight, modern, client-side QR code and Barcode generator built with pure HTML5, CSS3, and JavaScript. Generate single codes, customize styles, or batch-create hundreds of QR codes and barcodes simultaneously with instant ZIP export.

---

## Features

- **Single QR Code Generator**
  - Instant live generation with debounced input.
  - Custom pixel resolution (160px to 600px HD).
  - Configurable error correction levels (L, M, Q, H).
  - Custom foreground and background color pickers.
  - Direct PNG download and one-click clipboard copy.

- **Barcode Generator**
  - Multi-standard symbology support: `CODE128`, `EAN-13`, `UPC-A`, `CODE39`, `ITF-14`, and `Pharmacode`.
  - Toggle human-readable text labels below bars.
  - Custom line and canvas background colors.
  - Export as crisp PNG or copy directly to clipboard.

- **Bulk QR Code Generation**
  - Line-delimited batch generation from raw text or URLs.
  - Responsive visual preview grid with item indexing.
  - Instant asynchronous client-side `.zip` packaging for all generated codes.

- **Bulk Barcode Generation**
  - Multi-line batch generation tailored for inventory, SKU, and asset tracking.
  - Global format selection across all bulk items.
  - 1-click batch export to a structured `.zip` archive.

- **Modern & Fluid Interface**
  - Glassmorphic UI with smooth tab transitions and responsive CSS grid.
  - Dark and Light theme toggle with automatic persistence via `localStorage`.
  - Zero server dependency — 100% runs inside the client browser.

---

## Tech Stack & Dependencies

- **HTML5 & Vanilla JavaScript (ES6+)**
- **Modern CSS3** (Custom properties, CSS Grid, Flexbox, Backdrop filters)
- **Libraries used via CDN:**
  - [QRCode.js](https://cdnjs.com/libraries/qrcodejs) — Dynamic QR code rendering.
  - [JsBarcode](https://lindell.me/JsBarcode/) — Multi-format SVG/Canvas barcode engine.
  - [JSZip](https://stuk.github.io/jszip/) — In-browser file compression and ZIP creation.

---

## Getting Started

### Prerequisites

No build tools, Node.js packages, or local web servers are required. You only need a modern web browser (Chrome, Firefox, Safari, Edge).
