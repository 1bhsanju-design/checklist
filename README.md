[README.md](https://github.com/user-attachments/files/23893972/README.md)
# TGS/TMP Review Checklist

An interactive workflow checklist for Traffic Guidance Schemes (TGS) and Traffic Management Plans (TMP). This tool facilitates a multi-role review system with guided handover, auto-save, and reporting capabilities.

## Features

- **Multi-Role Workflow**: Specialized views and checklists for Designers, Checkers, Traffic Management Designers (TMD), Road Authorities, and Final Approvers.
- **Interactive Checklists**: Comprehensive validation for TGS and TMP requirements.
- **Progress Management**:
  - Auto-save functionality to local storage.
  - Export/Import progress via JSON files.
- **Reporting**: Generate PDF reports and final summaries.
- **User Interface**:
  - Dark/Light mode toggle.
  - Responsive design for various devices.
  - "Glassmorphism" UI aesthetics.
- **AI Assistant**: Integrated AI chat interface for assistance.

## Usage

1. **Open the Application**: Simply open `TGS_TMP Checklist_3.html` in any modern web browser (Chrome, Edge, Firefox, Safari). No server installation is required.
2. **Select Role**: Choose your role (e.g., Designer, Checker) to see relevant checklist items.
3. **Manage Suites**: Create multiple suites for different parts of your project.
4. **Review & Sign-off**: Complete the checklist items and digitally sign off sections.
5. **Save/Load**: Use the "Save Progress" button to download a JSON file of your current state. Load it later to resume work.

## Technical Details

- **Single File Application**: All logic, styling, and structure are contained within a single HTML file for easy portability.
- **Dependencies**: Uses CDN links for:
  - `pako` (Compression)
  - `html2pdf.js` (PDF Generation)
  - Google Fonts

## Author

**Crompton Concepts**
