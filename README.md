# Visonic PmaxService Documentation

## Overview
This project provides comprehensive technical documentation for the Visonic Alarm System, including both the Powerlink API (JSON-RPC) and the Visonic REST API. It is built using [MkDocs](https://www.mkdocs.org/) with the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

The documentation is intended for developers, integrators, and advanced users who need to interface with Visonic PowerMaster GTX panels, PowerLink3 modules, and Powermanage servers.

> **Note:** This site is a work in progress and may contain outdated or incomplete information. Please verify requests before using them on production devices.

## Features
- **Powerlink API Documentation:**
  - JSON-RPC interface for Powerlink modules
  - Method reference with example requests and responses
- **Visonic REST API Documentation:**
  - REST endpoints for user and installer applications
  - Authentication, device management, and panel operations
  - Example requests and responses
- **Error Codes:**
  - Common error responses and their meanings
- **Versioning:**
  - Supported API versions and endpoints

## Project Structure
```
visonic-pmaxservice-docs/
├── docs/
│   ├── index.md                # Project introduction and overview
│   ├── powerlink-api/          # Powerlink API docs (introduction, methods)
│   └── visonic-api/            # Visonic REST API docs (introduction, endpoints, versions)
├── mkdocs.yml                  # MkDocs configuration
├── requirements.txt            # Python dependencies
├── errors.json                 # Example error responses
├── to-add.json                 # Planned/undocumented API methods
├── visonic-api-todo.txt        # TODOs and endpoints to investigate
```

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