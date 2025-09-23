# Visonic PmaxService Documentation

## Overview
This project provides comprehensive technical documentation for the Visonic Alarm System, including both the Powerlink API (JSON-RPC) and the Visonic REST API. It is built using [MkDocs](https://www.mkdocs.org/) with the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

The documentation is intended for developers, integrators, and advanced users who need to interface with Visonic PowerMaster GTX panels, PowerLink3 modules, and Powermanage servers.

> **Note:** This site is a work in progress and may contain outdated or incomplete information. Please verify requests before using them on production devices.

## Features
- **Central hub for Visonic docs:** Links to detailed PowerManage and PowerLink API docs
- **Local articles:** Focused guides hosted in this repo (see `docs/`)
- **Artifacts:** JSON files for errors and items to investigate (`errors.json`, `to-add.json`)

## Project Structure
```
visonic-pmaxservice-docs/
├── docs/
│   ├── index.md                                        # Site home
│   └── visonic-nextcam-k9pg2-powerlink-ftp-images-audio.md  # Guide for Next CAM K9 PG2
├── mkdocs.yml                  # MkDocs configuration
├── requirements.txt            # Python dependencies
├── errors.json                 # Example error responses
├── to-add.json                 # Planned/undocumented API methods
├── visonic-api-todo.txt        # TODOs and endpoints to investigate
```

Note: `docs_old/` contains legacy content kept for reference and is not part of the current site build.

## Getting Started
### Prerequisites
- Python 3.7+

### Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/rexchoppers/visonic-pmaxservice-docs.git
   cd visonic-pmaxservice-docs
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Serve the documentation locally:
   ```sh
   mkdocs serve
   ```
   Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Usage
- Browse the documentation for detailed API references, including authentication, endpoints, parameters, and example requests/responses.
- The documentation covers both the Powerlink JSON-RPC API and the Visonic REST API (user and installer endpoints).
- Refer to the navigation sidebar for available sections and methods.

## Useful links
- PowerManage API Docs: https://rexchoppers.github.io/docs-powermanage-api
- PowerLink API (OpenRPC Playground): https://playground.open-rpc.org/?schemaUrl=https://raw.githubusercontent.com/rexchoppers/docs-powerlink-api/dist/openrpc.build.json
- Article – Accessing Images/Audio from Visonic Next CAM K9 PG2: docs/visonic-nextcam-k9pg2-powerlink-ftp-images-audio.md
- Community – Home Assistant Visonic integration: https://github.com/davesmeghead/visonic
- Maintainer site: http://www.rexchoppers.com

## Contributing
Contributions are welcome! To add or update documentation:
1. Fork the repository
2. Create a new branch
3. Add or edit Markdown files in the `docs/` directory
4. Update `mkdocs.yml` if you add new pages
5. Submit a pull request

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Credits
- [davesmeghead](https://github.com/davesmeghead/visonic) – For the Home Assistant integration inspiration
- [cfalas](https://github.com/cfalas) - PR Contributions
- [My Site](http://www.rexchoppers.com)

---
For questions or suggestions, please open an issue or contact the maintainer. 