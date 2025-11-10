# Forest Carbon Offset Workshop Handouts

This repository packages the publicly shareable materials for the Forest Carbon Offset
workshop. Participants will find the combined handout PDF and a reference library of the
primary protocol documents discussed during the session.

## Quick Access

Scan the QR code below to open this repository directly on your mobile device:

![Workshop materials QR code](https://api.qrserver.com/v1/create-qr-code/?size=240x240&data=https%3A%2F%2Fgithub.com%2FUBC-FRESH%2Fforest-carbon-offset-protocol-summaries-publish)

## Contents

- `outputs/forest-offset-handout.pdf` – consolidated handout summarising the four standards
  reviewed in the workshop.
- `outputs/forest-offset-vulnerabilities.pdf` – companion briefing outlining potential
  vulnerabilities and discussion prompts for each standard, organised by the KPI
  framework.
- `reference/` – supporting protocol documents and tools sourced from the programme owners.

## Protocol Resources

| Protocol | Description | Official Source |
| --- | --- | --- |
| B.C. Forest Carbon Offset Protocol (2024) | Province of British Columbia compliance protocol | https://www2.gov.bc.ca/gov/content/environment/climate-change/industry/offsets/forest-carbon-offset-protocol |
| Verra – Verified Carbon Standard (VCS) | Global voluntary carbon market programme | https://verra.org/project/vcs-program/ |
| Gold Standard for the Global Goals | Sustainable development & carbon certification standard | https://www.goldstandard.org/ |
| Climate Action Reserve – U.S. Forest Protocol | North American compliance/voluntary offset protocol | https://www.climateactionreserve.org/how/protocols/forest/ |

Each document in the `reference/` directory includes a comment in the file list indicating the
source and version where applicable. Please consult the links above for the latest official
versions and programme updates.

## License & Attribution

All materials are distributed under the Creative Commons Attribution 4.0 International (CC BY
4.0) licence. When reusing content, please attribute to the workshop organisers and the
original protocol authors.

## Rebuilding the Package

From the parent repository, run:

```bash
scripts/build-handout.sh
make all
```

The build script regenerates the handout PDF, and `make all` synchronises the PDF and
reference files into this publication repository.
