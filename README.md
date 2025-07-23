# Wikidata Electronic Literature JSON Schema

This repository contains a JSON Schema for representing electronic literature works in Wikidata format, based on the data model from the [CELL (Center for Electronic Literature and Locative Media) WikiProject](https://www.wikidata.org/wiki/Wikidata:WikiProject_Digital_Narratives/CELL).

## Key Properties for Electronic Literature

The schema includes all properties from the CELL data model, organized into categories.

### Basic Bibliographic Information

- `P31` (instance of) - Type of work (e.g., creative work)
- `P1476` (title) - Official title
- `P50` (author) - Author(s)
- `P136` (genre) - Literary genre
- `P407` (language) - Language of the work
- `P577` (publication date) - When published
- `P571` (inception) - When created

### Technical Properties

- `P400` (platform) - Computing platform
- `P277` (programmed in) - Programming language
- `P306` (operating system) - Required OS
- `P2701` (file format) - File formats
- `P408` (software engine) - Game/media engine used
- `P479` (input device) - Required input devices
- `P5196` (output device) - Required output devices

### Digital Media Properties

- `P12548` (media modality) - Visual, audio, haptic, etc.
- `P953` (work available at URL) - Access URL
- `P4945` (download URL) - Download link
- `P1324` (source code repository URL) - Code repository
- `P856` (official website) - Official site

### Publication & Distribution

- `P123` (publisher) - Publisher
- `P1433` (published in) - Publication venue
- `P275` (copyright license) - License
- `P166` (award received) - Awards
- `P179` (part of series) - Series membership

### Identification & Cataloging

- `P12204` (ELMCIP ID) - Electronic Literature Organization ID
- `P356` (DOI) - Digital Object Identifier
- `P10832` (WorldCat Entities ID) - WorldCat identifier
- `P243` (OCLC number) - OCLC control number

### Relationships

- `P747` (has edition or translation) - Related editions
- `P629` (edition or translation of) - Original work
- `P361` (part of) - Larger work this belongs to
- `P767` (contributor) - Contributors
- `P655` (translator) - Translators

### Content & Analysis

- `P921` (main subject) - Subject matter
- `P1552` (has characteristic) - Notable characteristics
- `P8371` (references work) - Referenced works/theories
- `P7081` (quotation or excerpt) - Notable quotes

## Data Types

The schema supports all Wikidata data types:

- **Entity references** (`wikibase-entityid`) - Links to other Wikidata items
- **Strings** (`string`) - Simple text values
- **URLs** (`string` with URI format) - Web addresses
- **Times** (`time`) - Dates and timestamps
- **Quantities** (`quantity`) - Numerical values with units
- **Coordinates** (`globecoordinate`) - Geographic locations
- **Monolingual text** (`monolingualtext`) - Text in a specific language
- **Commons media** (`string`) - Wikimedia Commons file names

## Related Resources

- [Wikidata:WikiProject Digital Narratives/CELL](https://www.wikidata.org/wiki/Wikidata:WikiProject_Digital_Narratives/CELL)
- [Electronic Literature Organization](https://eliterature.org/)
- [ELMCIP (Electronic Literature as a Model of Creativity and Innovation in Practice)](https://elmcip.net/)
- [Wikidata Data Model](https://www.wikidata.org/wiki/Wikidata:Data_model)

## License(s)

All structured data is licensed under Creative Commons CC0 License.

Descriptions and documentation is released under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license.

Validator code is released under the MIT license.
