# Legacy PHP System Maintenance & Development

This project focuses on maintaining and extending a **Legacy PHP system** inherited from an external developer. The main objective was to fix existing bugs and improve the system so that it could fully operate according to the requirements of the **Insurance Department and Nursing Department**.

---

## Key Achievements

* **System Recovery:** Investigated routes, controllers, and PHP files to identify and resolve **HTTP 404 errors**, successfully restoring the system to a functional state.
* **Large-Scale Code Modification:** Modified and optimized more than **45+ PHP files** to restore and improve the system's functionality.
* **Real-World User Collaboration:** Worked directly with the **Insurance and Nursing Departments** under real-time pressure to translate user requirements into practical and functional system features.

---

## Project Structure

```text
├── ita-data/           # ITA-related data and system management
├── main-menu/          # Main menu structure
├── pages/              # PHP files for individual web pages
├── tb/                 # Database and table-related components
├── varaiable/          # Additional variable configuration files
├── index.php           # Main entry point of the system
├── index-xs.php        # Entry point for small/mobile screens
└── variable-ita.php    # Variables specific to the ITA system
```
---

## Tech Stack

- **PHP** (Legacy Version) — Backend development and server-side logic
- **HTML / CSS / JavaScript** — Frontend development and user interface
- **ITA (Integrity and Transparency Assessment)** — A system developed in accordance with ITA standards used by the Ministry of Public Health


---

## Debugging & Troubleshooting Process

When an **HTTP 404 error** was encountered, the issue was investigated by tracing the application's file structure and execution flow.

```mermaid
flowchart TD
    A["HTTP 404 Error"] --> B["Inspect index.php"]
    B --> C["Trace included PHP files"]
    C --> D["Check ita-data/"]
    D --> E["Check tb/"]
    E --> F["Identify missing or incorrect file paths"]
    F --> G["Modify PHP files"]
    G --> H["Test the affected functionality"]
    H --> I["System restored successfully"]
```
