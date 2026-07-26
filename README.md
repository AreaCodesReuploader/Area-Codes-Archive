# Area Codes Archive

This repository preserves the original, reuploaded, and archived versions of **“Area Codes // dreamwastaken”** by **@ihaveajuicebox**.

It serves as a forever home for:

* Original Wattpad chapter links
* Reuploaded Wattpad chapter links
* Archive.today captures of the original story
* Locally saved Wattpad chapters in HTML format
* Companion folders associated with saved HTML pages
* Cover images and chapter images
* Bing cache web captures
* YouTube chapter readings that were useful during the reupload process
* The planned Archive of Our Own edition
* Downloadable editions generated from the completed archive

This repository does not claim authorship of the story.

## Project Status

The archive is currently being organized and prepared for an eventual Archive of Our Own upload.

Some materials are complete, while others still need to be:

* Located
* Identified
* Matched to chapters
* Deduplicated
* Converted
* Reviewed
* Uploaded

See [`TODO.md`](TODO.md) for the active preservation and upload checklist.

## External Links

### Wattpad

* [Original Wattpad story][1] — currently unavailable
* [Wattpad reupload][2]

### Archive of Our Own

* AO3 reupload — planned
* AO3 chapter-by-chapter edition — planned
* AO3 downloadable editions — planned

### Internet Archive and Wayback Machine

* Internet Archive compiled edition — planned
* Wayback Machine capture of the AO3 work — planned
* Wayback Machine capture of AO3 chapter pages — planned
* Wayback Machine capture of AO3 download links — planned

### YouTube Chapter Readings

A number of YouTube videos contained readings of chapters from the story and were useful when reconstructing or checking the reuploaded version.

These will be indexed in:

```text
Links/YouTube Readings/README.md
```

The index should preserve:

* Video title
* Channel name
* Original YouTube URL
* Archived URL, when available
* Chapter or chapter range covered
* Upload date, when known
* Current availability
* Notes about audio quality or missing sections
* Whether the reading was used to verify the reupload

Known playlists, channels, and individual video links will be added as they are located.

## Repository Contents

### Links

The `Links/` directory contains chapter-by-chapter indexes and external references.

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

Many of these URLs are now dead, but they are preserved because they contain the original story and chapter IDs and are useful for archival matching.

#### `Links/Reupload/`

Contains the live Wattpad reupload story and chapter URLs.

These links will be matched chapter-by-chapter against the original version.

#### `Links/Webpage Captures/`

Contains links to Archive.today and other external webpage captures of the original story.

This directory contains indexes and URLs, not the locally saved HTML files themselves.

#### `Links/YouTube Readings/`

Contains links to chapter readings uploaded to YouTube.

These recordings may be useful for:

* Confirming chapter text
* Recovering missing wording
* Confirming chapter order
* Identifying chapter breaks
* Comparing the original and reuploaded versions
* Locating missing author notes or dialogue

## Planned Repository Structure

```text
Area-Codes-Archive/
├── README.md
├── TODO.md
├── NOTICE.md
├── ATTRIBUTIONS.md
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
│   ├── Chapter Fifteen/
│   │   ├── Area Codes __ dreamwastaken - fifteen - Wattpad.html
│   │   └── Area Codes __ dreamwastaken - fifteen - Wattpad_files/
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

This is a planned structure. Empty folders do not need to be created until files are ready to be added.

## Saved Chapters

The `Saved Chapters (HTML)/` directory contains locally saved Wattpad pages.

Whenever an HTML download has an associated `_files` folder, the HTML file and companion folder should remain together.

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

Some companion folders may be empty. They should not be deleted until the HTML file has been reviewed and tested.

## Images

The `Images/` directory preserves:

* Original cover variants
* Images embedded inside chapters
* Possible chapter images that have not yet been identified
* Images recovered from saved HTML companion folders
* Images recovered from screenshots, phone storage, or cloud backups

Confirmed chapter images should be stored separately from unidentified candidates.

## Web Captures

The `Web Captures/` directory contains saved screenshots or image-based captures rather than ordinary HTML pages.

This includes:

* Bing cache captures
* Archive.today screenshots or downloads
* Unidentified web captures
* Other cached page images

Original filenames should be preserved until each capture has been identified.

## AO3 Edition

The `AO3/` directory will contain the working files for the Archive of Our Own edition.

This will include:

* Work metadata
* Chapter ordering
* Cleaned chapter text
* Chapter-specific notes
* Image placement records
* Upload progress
* Final AO3 links

The AO3 upload will be performed manually after the archive has been reviewed.

## Downloads

The `Downloads/` directory will contain downloadable versions of the completed archive or AO3 edition.

Planned formats include:

* EPUB
* PDF
* HTML
* AZW3
* MOBI

Files will be added only after the full chapter set and formatting have been verified.

## Preservation Rules

1. Preserve original filenames wherever practical.
2. Record original filenames when files are renamed.
3. Keep downloaded HTML files with their associated `_files` folders.
4. Do not assume an empty companion folder is unnecessary until the page has been tested.
5. Preserve duplicates until hashes confirm that they are identical.
6. Keep dead original URLs because their IDs remain historically useful.
7. Preserve original source files before editing or converting them.
8. Place uncertain material in an `Unidentified` folder instead of deleting it.
9. Record the source and purpose of files whenever known.
10. Keep YouTube reading links even when the videos are unavailable, provided the original URLs or identifiers survive.
11. Preserve archived video links separately from live YouTube links.
12. Do not automatically scrape Wattpad when local files or archived pages can be used instead.

## Attribution and Rights

“Area Codes // dreamwastaken” was written by **@ihaveajuicebox**.

This repository is an archival and preservation project. It does not claim authorship of the story and does not grant a new license over the original work.

Any scripts, indexes, manifests, or original documentation added to this repository may be separately licensed later.

## AI-Assisted Work

Artificial intelligence tools were used during the creation and organization of this repository.

AI assistance may have been used for:

* Drafting and revising repository documentation
* Generating or refining scripts
* Extracting and formatting chapter links
* Comparing link patterns
* Planning the repository structure
* Producing checklists and manifests
* Assisting with file-inventory and metadata-processing workflows

All AI-assisted output should be reviewed by a human before it is relied upon, committed, or used in the Archive of Our Own reupload.

AI tools were not the original author of “Area Codes // dreamwastaken” and are not credited as such (LLMs weren't even publicly available at the time to non-technical individuals. Only a scant few APIs). The original story remains the work of **@ihaveajuicebox**.

Human contributors, archival sources, and tool usage are documented in [`ATTRIBUTIONS.md`](ATTRIBUTIONS.md).


[1]: https://www.wattpad.com/story/251081626-area-codes-dreamwastaken
[2]: https://www.wattpad.com/story/350625442-area-codes-dreamwastaken-reuploaded
