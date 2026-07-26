# Area Codes Archive

This repository preserves the original, reuploaded, and archived versions of **“Area Codes // dreamwastaken”** by **@ihaveajuicebox**.

It serves as a long-term home for:

* Original Wattpad story and chapter links
* The completed Wattpad reupload
* Archive.today captures of the original story
* Locally saved Wattpad chapters in HTML format
* Companion folders associated with saved HTML pages
* Cover images and chapter images
* Bing cache web captures
* YouTube chapter readings used during reconstruction
* The planned Archive of Our Own edition
* Downloadable archival editions

This repository does not claim authorship of the story.

## Project Status

The complete Wattpad reupload has already been reconstructed and published by the repository maintainer.

That reconstruction was completed personally using surviving material gathered from several sources, including:

* Cached versions of the original story
* Locally saved Wattpad pages
* YouTube chapter readings
* Original chapter links
* Archived pages
* The final chapters briefly reposted by the original author before being removed again

The current project is focused on organizing and preserving the source material, documenting how the reconstruction was completed, preparing the AO3 edition, and producing durable archival copies.

See:

* [`TODO.md`](TODO.md) for remaining work
* [`CREDITS.md`](CREDITS.md) for contributor and tool credits
* [`NOTICE.md`](NOTICE.md) for authorship and archival-purpose information
* [`SOURCES.md`](SOURCES.md) for reconstruction sources and provenance

## External Links

### Wattpad

* [Original Wattpad story][1] — currently unavailable
* [Completed Wattpad reupload][2]

### Archive of Our Own

* AO3 reupload — planned
* AO3 downloadable editions — planned

### Internet Archive and Wayback Machine

* Internet Archive compiled edition — planned
* Wayback Machine capture of the AO3 work — planned
* Wayback Machine captures of relevant YouTube reading pages — planned where available

## Repository Contents

### `Links/`

Contains chapter-by-chapter link indexes and external references.

```text
Links/
├── Original/
│   └── README.md
├── Reupload/
│   └── README.md
├── Webpage Captures/
│   └── README.md
└── YouTube Readings/
    └── README.md
```

#### `Links/Original/`

Contains the original Wattpad story and chapter URLs.

Many of these links are now dead, but they are preserved because the original story and chapter IDs remain useful for matching archived pages and reconstruction sources.

#### `Links/Reupload/`

Contains the live links for the completed Wattpad reupload.

#### `Links/Webpage Captures/`

Contains links to Archive.today and other external webpage captures.

This folder contains indexes and URLs, not the locally saved HTML files themselves.

#### `Links/YouTube Readings/`

Contains links to YouTube chapter readings used during reconstruction or verification.

Each entry should record:

* Video title
* Channel name
* Original URL
* Archived URL, when available
* Video ID
* Chapter or chapter range
* Current availability
* How the recording was used

## Planned Repository Structure

```text
Area-Codes-Archive/
├── README.md
├── TODO.md
├── NOTICE.md
├── CREDITS.md
├── SOURCES.md
│
├── Links/
│   ├── Original/
│   │   └── README.md
│   ├── Reupload/
│   │   └── README.md
│   ├── Webpage Captures/
│   │   └── README.md
│   └── YouTube Readings/
│       └── README.md
│
├── Saved Chapters (HTML)/
│   ├── README.md
│   ├── Chapter One/
│   │   ├── Area Codes __ dreamwastaken - one - Wattpad.html
│   │   └── Area Codes __ dreamwastaken - one - Wattpad_files/
│   └── ...
│
├── Images/
│   ├── README.md
│   ├── Cover/
│   │   ├── original-cover-288x450.jpg
│   │   └── original-cover-64x100.jpg
│   ├── Chapter Images/
│   └── Unidentified/
│
├── Web Captures/
│   ├── README.md
│   ├── Archive Today/
│   ├── Bing Cache/
│   └── Unidentified/
│
├── AO3/
│   ├── README.md
│   ├── Metadata.md
│   ├── Chapter Checklist.md
│   └── Chapters/
│
├── Downloads/
│   ├── README.md
│   ├── EPUB/
│   ├── PDF/
│   ├── HTML/
│   ├── AZW3/
│   └── MOBI/
│
├── Notes/
│   ├── README.md
│   ├── Alternate Links/
│   ├── Chapter Fragments/
│   └── Research/
│
└── Scripts/
    └── README.md
```

This is a planned structure. Empty folders do not need to be created before files are ready to be added.

## Saved HTML Pages

The `Saved Chapters (HTML)/` directory contains locally saved Wattpad pages.

Whenever an HTML file has an associated `_files` folder, the HTML file and companion folder should remain together.

Example:

```text
Saved Chapters (HTML)/
└── Chapter Fifty-Eight/
    ├── Area Codes __ dreamwastaken - fifty-eight - Wattpad.html
    └── Area Codes __ dreamwastaken - fifty-eight - Wattpad_files/
```

Companion folders may contain:

* Images
* Stylesheets
* Scripts
* Thumbnails
* Cached page resources
* Other assets referenced by the saved HTML

Some companion folders may be empty. They should not be removed until the corresponding HTML page has been inspected and tested.

## Images

The `Images/` directory preserves:

* Original cover variants
* Images embedded in chapters
* Images recovered from saved HTML resource folders
* Images recovered from screenshots, caches, phone storage, or cloud backups
* Unidentified images that may belong to the story

Confirmed chapter images should be stored separately from uncertain candidates.

## Web Captures

The `Web Captures/` directory contains saved screenshots or image-based captures rather than ordinary chapter HTML pages.

This includes:

* Bing cache captures
* Archive.today captures saved as images or downloads
* Unidentified screenshots
* Other cached page images

Original filenames should be preserved until the capture has been identified.

## AO3 Edition

The `AO3/` directory will contain the working files for the Archive of Our Own edition.

This will include:

* Work metadata
* Chapter ordering
* Cleaned chapter text
* Chapter-specific source notes
* Image-placement records
* Upload progress
* Final AO3 links

The AO3 upload will be completed manually after the repository materials have been reviewed.

## Downloads

The `Downloads/` directory will contain downloadable versions of the completed AO3 or archival edition.

Planned formats include:

* EPUB
* PDF
* HTML
* AZW3
* MOBI

## AI-Assisted Work

Artificial intelligence tools were used during the creation and organization of this repository.

AI assistance has included:

* Drafting and revising Markdown documentation
* Planning the repository structure
* Formatting chapter-link indexes
* Comparing URL patterns
* Explaining recovered timestamps
* Generating and refining scripts
* Creating file-inventory and duplicate-detection workflows
* Assisting with image-dimension checks
* Planning local HTML metadata extraction
* Producing preservation and AO3-preparation checklists

AI tools did not write the original story and are not credited as authors of it.

All AI-assisted output should be reviewed by a human before it is committed, executed, or used in publication.

Further details are recorded in [`CREDITS.md`](CREDITS.md).

## Preservation Rules

1. Preserve original filenames wherever practical.
2. Record original filenames when files are renamed.
3. Keep downloaded HTML files with associated `_files` folders.
4. Do not assume an empty companion folder is unnecessary until the page has been tested.
5. Preserve duplicates until hashes confirm they are identical.
6. Keep dead original URLs because their IDs remain useful.
7. Preserve untouched source files before cleaning, converting, or editing them.
8. Place uncertain material in an `Unidentified` folder instead of deleting it.
9. Record the source and purpose of each file whenever known.
10. Keep YouTube reading links and video IDs even when videos become unavailable.
11. Keep large video files outside the Git repository.
12. Prefer processing local files over automatically scraping Wattpad.

## Attribution and Rights

“Area Codes // dreamwastaken” was written by **@ihaveajuicebox**.

This repository is an archival and preservation project. It does not claim original authorship and does not grant a new license over the story.

See [`NOTICE.md`](NOTICE.md) for the full notice.

[1]: https://www.wattpad.com/story/251081626-area-codes-dreamwastaken
[2]: https://www.wattpad.com/story/350625442-area-codes-dreamwastaken-reuploaded
