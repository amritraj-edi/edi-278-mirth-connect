# X12 278 to XML with Mirth Connect

## Overview
Portfolio demonstration of a Mirth Connect channel designed to parse selected fields from an ANSI X12 278 health care services review/request transaction and produce an XML representation.

## Included
- `Channels/EDI278 to XML Parsing.xml` — exported channel configuration
- `Sample Data/Sample EDI 278.txt` — synthetic X12 278 example
- `Sample Data/README.md` — sample-data disclaimer

## How to review
Inspect the channel XML in a compatible Mirth Connect environment. Run only in a non-production environment with synthetic test data and confirm output against the applicable implementation guide and trading-partner requirements.

## Data handling
Original result files were excluded. The embedded channel test template was replaced with the synthetic sample included in this repository. This repository uses fabricated example values. Never commit production EDI, PHI, credentials, endpoint URLs, or client-specific details.

## Limitations
- Demonstrates selected-field mapping; it is not a complete X12 278 parser or a certified validator.
- Actual authorization workflows may require additional segments, loops, code-set validation, and companion-guide rules.
- The generated XML is a mapping-specific representation, not an official standard XML schema.

## Portfolio summary
Configured a Mirth Connect channel to parse selected ANSI X12 278 service-review fields and map them into XML, with a synthetic test transaction for demonstration.

## Provenance note
This originated as a technical assignment. Confirm you have permission to publish the channel configuration and mapping logic. Keep the repository private until ownership and confidentiality are clear.
