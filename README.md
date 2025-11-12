# Forest Carbon Offset Workshop Handouts

This repository packages the publicly shareable materials for the Forest Carbon Offset
workshop. Participants will find the combined handout PDF and a reference library of the
primary protocol documents discussed during the session.

## Workshop Context

These resources accompany the UBC Sustainability Hub event
[Negotiation Innovation: Advancing Climate Action through Research and Learning](https://sustain.ubc.ca/events/negotiation-innovation-advancing-climate-action-through-research-and-learning).
They are distributed in draft form to encourage critical engagement; updated editions will
be published as peer review concludes.

## Quick Access

Scan the QR code below to open this repository directly on your mobile device:

![Workshop materials QR code](https://api.qrserver.com/v1/create-qr-code/?size=240x240&data=https%3A%2F%2Fubc-fresh.github.io%2Fforest-carbon-offset-protocol-summaries-publish%2F)

## Contents

- [Forest Offset Handout (PDF)](outputs/forest-offset-handout.pdf) – consolidated participant
  summary covering all four standards; optimised for printing.
- [Forest Offset Handout (Markdown)](outputs/forest-offset-handout.md) – same content in a
  mobile-friendly format.
- [Forest Offset Vulnerabilities Briefing (PDF)](outputs/forest-offset-vulnerabilities.pdf) –
  discussion prompts that surface potential design weaknesses.
- [Forest Offset Vulnerabilities Briefing (Markdown)](outputs/forest-offset-vulnerabilities.md) –
  Markdown version for quick browsing.
- [Reference Library](reference) – supporting protocol documents and tools sourced from the
  programme owners.

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

---

_Acknowledgement_: These materials were assembled with assistance from an LLM coding agent.
Content remains under active collaborator review; expect revisions as feedback is incorporated.

## Rebuilding the Package

From the parent repository, run:

```bash
scripts/build-handout.sh
make all
```

The build script regenerates the handout PDF, and `make all` synchronises the PDF and
reference files into this publication repository.
