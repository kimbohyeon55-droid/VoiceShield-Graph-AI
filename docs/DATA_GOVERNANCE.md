# Data governance

The project treats acquisition, training eligibility, and permission to publish as separate decisions. This package contains no dataset, transcript excerpt, row-level example, audio recording, derived corpus, model weights, or private evidence log.

## Data classes

| Class | Intended role | Limitation |
|---|---|---|
| Real public data | Potential research input after provenance, rights, privacy, and task review | Being publicly downloadable is insufficient |
| Synthetic experiment data | Controlled tests of methods and workflow | Does not establish real victim behaviour or field performance |
| Public statistics | Background and trend context | Aggregate counts are not labelled conversations or graph edges |

The latest documented harvest did not establish an eligible Korean phishing/normal corpus for the intended task. It also did not establish a usable domestic voice-phishing relationship graph. The later synthetic prototypes do not change those findings.

## Restrictions considered

- **Original-source rights:** A code license does not automatically cover audio, transcripts, screenshots, or data referenced by a repository. A paper's license is likewise not a dataset license.
- **Purpose and contest use:** Research permission may not resolve prize-related use, sponsor rights, public submission, or release of derived artifacts. An exact competition agreement was not available in the reviewed project.
- **Provider access conditions:** AI Hub and other controlled-access sources can require identity, application, purpose, and approval checks. Its general policy also addresses unapproved third-party access and overseas transfer. [AI Hub policy](https://aihub.or.kr/intrcn/guid/usagepolicy.do?currMenu=151&topMenu=105)
- **Open licenses and privacy:** Copyright permission does not by itself clear personal-data, privacy, or publicity rights. [CC BY 4.0 legal code, section 2(b)](https://creativecommons.org/licenses/by/4.0/legalcode.en)
- **Source-specific limits:** Earlier audits recorded unresolved provider terms for financial-regulator recordings and noncommercial or derivative-use conditions for some research datasets. These remain unresolved; this portfolio does not reapprove them.

## Privacy handling

Potentially identifying content includes names, voices, financial details, phone/account numbers, URL parameters, third-party information, and relationships that support reidentification. Masking obvious patterns is not a complete clearance method. Pseudonymous graph identifiers can still reveal relationships when combined with other information.

The public package uses newly written summaries and conceptual diagrams. Even synthetic text, statistics files, screenshots, and cached terms are excluded from the release payload to avoid accidental source content or rights assumptions.
