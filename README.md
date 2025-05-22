# Parser for Industrial Control Systems Network Protocol

The goal is to develop and share parsers for Industrial Control Systems Network Protocol Parsers  (ICSNPP) in zeek.\
There are several ways to contribute:

- Report errors (and fixes if possible) by GitHub issues/ pull requests
- provide useful enhancements by pull requests
- new parsers by GitHub issue

In order to test a parser a corresponding pcap is required.

## Overview ICSNPP Packages

Industrial Control Systems protocol parsers plugins for the Zeek network security monitoring framework using [Spicy](https://docs.zeek.org/projects/spicy/en/latest/).

The following parsers are currently provided:

- [IEC 60870-5-104](https://github.com/DINA-community/icsnpp-ice104)
- [IEC 61850](/IEC61850)
  - [IEC 61850 MMS](https://github.com/DINA-community/icsnpp-iec61850-mms)
  - [IEC 61850-9-2 Sampled Values](https://github.com/DINA-community/icsnpp-iec61850-sv)
  - [IEC 61850-8-1 GOOSE](https://github.com/DINA-community/icsnpp-iec61850-goose)
- [HART-IP](https://github.com/DINA-community/icsnpp-hartip)
- Utilities
  - [ASN.1](https://github.com/DINA-community/icsnpp-util)

## Getting started

Navigate to the specific protocol repository to get a README about the implemented functions and metadata.

## Important Notes

The Parsers where developed within a IT/OT-Lab environment, under usage of real, captured network traffic.
Remember that your live plant and network traffic might differ from our tested cases, due to a lack of reliant network data, which might result in unexpected behavior of the parsers. In such a case we encourage you to participate in our cause by improving the given parsers.

## License

The software was developed on behalf of the [BSI](https://www.bsi.bund.de) \(Federal Office for Information Security\)

Copyright (c) 2023-2025 by DINA-Community BSD 3-Clause License. [See License](/LICENSE)
