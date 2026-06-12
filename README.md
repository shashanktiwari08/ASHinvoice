# Invoice Generator

A premium, responsive, and dynamic client-side Invoice Generator designed specifically for boutique and luxury event management, catering, and decoration brands. This single-page application allows hosts to generate high-fidelity tax invoices and general bills on-the-go from any smartphone or desktop.

## 🚀 Features

- **Multi-Brand Workspace**: Select between predefined profiles:
  - ✈ **Aerosky Hospitality**: Pre-configured with GSTIN, tax types (CGST/SGST/IGST), and formal luxury themes.
  - 🍽 **Dev Caterers & Decorators**: Pre-configured for corporate & wedding event billing (non-tax invoicing).
- **Responsive & Adaptive Layout**:
  - **Desktop**: Clean side-by-side structures, tabular inputs, and side overlays.
  - **Smartphone**: Form fields stack elegantly, and line items convert into intuitive card layouts to easily input data on touch screens.
- **Proportional A4 Live Preview**:
  - Automatically scales the A4 page layout proportionally using viewport size listeners, providing a pixel-perfect, zero-scroll desktop-like representation on mobile screens.
- **Zero-Dependency PDF Export**:
  - High-resolution client-side PDF compiler using the off-screen Canvas SVG `foreignObject` rendering method.
  - Instantly compiles and downloads raw PDF binary streams natively without bloating the client with external libraries.
- **Dynamic Calculation Engine**: Instantly computes itemized amounts, tax rates, CGST/SGST allocations, subtotals, and net payables, with automatic number-to-words currency mapping.

---

## 🛠 Tech Stack

- **Core**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: Modern CSS3 (CSS Grid, Flexbox, Custom Media Breakpoints, CSS Variables)
- **Icons & Fonts**: Google Fonts (Playfair Display, DM Sans)
- **PDF Generation**: SVG rendering & manual PDF byte stream assembler

---

## 📦 Getting Started

This application is fully client-side and requires zero installation.

### Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/shashanktiwari08/ASHinvoice.git
   ```
2. Open `index.html` in your web browser:
   - On Windows: Double-click `index.html` or run `Start index.html` in PowerShell.
   - On Mac/Linux: Run `open index.html`.

---

## 📱 Smartphone vs. 💻 Desktop UI Layout

| Component | Desktop Experience | Smartphone Experience |
| :--- | :--- | :--- |
| **Grid Fields** | Horizontal grid tables | Collapsed vertical stacking |
| **Line Items** | Compact A4-styled table columns | Touch-friendly item cards with interactive fields |
| **Invoice Preview** | Fixed-width A4 layout | Scaled down using CSS transforms to fit the screen viewport |

---

## 📄 License

This project is licensed under the MIT License.
