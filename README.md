# DHI Taxonomic Notebook v1.0.0 - Taxonomy Knowledge Management 2026

> **DHI Taxonomic Notebook is a browser-based workspace for organizing biodiversity records, taxonomic notes, images, and relationships in an offline-friendly environment, now available in version 1.0.0.**

[![Platform](https://img.shields.io/badge/Platform-Browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/evanfjmvbaker9482/dhi-taxonomic-notebook-app?style=flat-square)](https://github.com/evanfjmvbaker9482/dhi-taxonomic-notebook-app)

---

<p align="center">
  <a href="https://evanfjmvbaker9482.github.io/dhi-taxonomic-notebook-app/">
    <img src="https://img.shields.io/badge/Download-DHI%20Taxonomic%20Notebook%20Latest-brightgreen?style=for-the-badge" alt="Download DHI Taxonomic Notebook">
  </a>
</p>

> **[Download DHI Taxonomic Notebook v1.0.0](https://evanfjmvbaker9482.github.io/dhi-taxonomic-notebook-app/)**

---

[Download Latest Build](https://evanfjmvbaker9482.github.io/dhi-taxonomic-notebook-app/)

---

## What It Does

DHI Taxonomic Notebook gives naturalists, botanists, and taxonomists a structured place to build and maintain collections of species and taxa. A hierarchical tree presents the larger classification, while the card-based view makes it easy to inspect individual entries, observations, and related information.

Because the application runs in a browser and keeps notebook content in local browser storage, it is suitable for offline-friendly workflows. Entries may contain Markdown or HTML notes, and images can be imported alongside records. JSON backup and transfer support helps move a notebook between sessions or installations.

---

## Key Capabilities

- Create taxonomy trees with multiple hierarchical levels.
- View taxa as cards and rearrange entries through drag-and-drop.
- Add formatted notes with Markdown or HTML.
- Keep application data in IndexedDB and localStorage.
- Import, organize, and preview images attached to taxonomic records.
- Transfer or back up datasets as JSON files with their associated images.
- Find species and taxon records through search.
- Maintain alternate names and synonyms for taxa.

---

## Getting Started

### Use the browser build

1. Visit the [latest build](https://evanfjmvbaker9482.github.io/dhi-taxonomic-notebook-app/).
2. Download or copy the project files into a local directory if you want a local copy.
3. Launch the primary HTML file with a modern browser.
4. Create a taxonomy tree, then add records, notes, and media.

### Get the source with Git

```bash
git clone https://github.com/evanfjmvbaker9482/dhi-taxonomic-notebook-app.git
cd REPO
```

Once the repository is available locally, open its main HTML entry point in a browser. If local-file security policies prevent some functionality, run the directory through a basic local static web server and visit the local URL it provides.

---

## Working with Your Notebook

A common setup process is:

1. Define the top-level taxon for the collection or research project.
2. Add subordinate taxa to establish the classification structure.
3. Open taxon cards and document findings with Markdown or HTML.
4. Add images and arrange them for easier inspection.
5. Search the notebook for species, taxa, and related records.
6. Enter synonyms when alternate taxon names should be preserved.
7. Export the notebook to JSON, including images, for backup or transfer.

For larger collections, combine both navigation styles. Use the tree to understand the overall classification, then use cards to examine, move, and manage individual entries.

---

## Data Storage and Configuration

There is no required configuration file. DHI Taxonomic Notebook is operated through its browser interface, with notebook information retained locally in two browser storage systems:

- **IndexedDB** stores application data and larger records.
- **localStorage** holds browser-local settings and supporting state.

Create JSON exports on a regular basis, especially before clearing site data, changing browsers, or maintaining an external copy of the notebook.

---

## Requirements

- A modern browser with JavaScript enabled.
- IndexedDB and localStorage support in the browser.
- Enough local storage for taxonomy records and imported images.
- No server-side runtime is needed for the browser build.
- A local static web server can help when browser restrictions interfere with opening files directly.

---

## Frequently Asked Questions

### Who can use DHI Taxonomic Notebook?

The notebook is designed for naturalists, botanists, taxonomists, and anyone keeping biodiversity or taxonomy-focused records.

### Does it work offline?

It is built for local, offline-friendly use in the browser. Download the build while connected, then open the local copy when an internet connection is unavailable.

### How can I transfer a notebook to another browser?

Use the export function to create a JSON file containing the notebook and its images. Import that file into the target browser or installation.

### Where does the application keep my data?

Records and application state are stored in the browser through IndexedDB and localStorage. Since clearing browser storage may delete locally retained information, keep JSON backups of important notebooks.

### Are formatted notes supported?

Yes. Notes may use Markdown or HTML formatting.

### What can I check if records appear to be missing?

Confirm that you are using the same browser profile and site context used when the records were created. If a JSON export is available, import it to restore the notebook.

### Where can I find new versions?

Open the [latest build](https://evanfjmvbaker9482.github.io/dhi-taxonomic-notebook-app/) and follow repository updates through [GitHub](https://github.com/evanfjmvbaker9482/dhi-taxonomic-notebook-app).

---

## Future Directions

Possible future work includes:

- Further improvements to taxonomy navigation and organization.
- More capable handling of notes and media.
- Added convenience for importing and exporting data.
- Continued usability work for biodiversity and botany research workflows.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
