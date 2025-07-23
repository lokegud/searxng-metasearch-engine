
Built by https://www.blackbox.ai

---

# SearXNG

## Project Overview
SearXNG is a privacy-respecting, hackable metasearch engine that aggregates results from various search engines while ensuring user privacy. It is designed to cater to both privacy-conscious users and developers looking to customize their search experience.

## Installation
To install SearXNG, ensure that you have Python 3.8 or higher and the necessary dependencies. You can set it up via pip with the following commands:

```bash
# Clone the repository
git clone https://github.com/searxng/searxng.git
cd searxng

# Install the required packages
pip install -r requirements.txt
```

### Development Dependencies
For development, install the additional dependencies listed in `requirements-dev.txt`:

```bash
pip install -r requirements-dev.txt
```

## Usage
Once installed, you can run SearXNG using the provided console script:

```bash
searxng-run
```

This will start the web application, and you can access it at `http://localhost:4000`.

## Features
- Aggregates search results from multiple engines
- Emphasizes user privacy by not tracking searches
- Customizable through settings and user interfaces
- Supports a variety of data formats and templates

## Dependencies
SearXNG has the following key dependency:

- `pyright`: ^1.1.391

Install this using the package manager of your choice or with pip as noted in the installation instructions above.

## Project Structure
The project is organized as follows:

```
searxng/
├── searx/                     # Main application module
│   ├── __init__.py
│   ├── webapp.py              # Entry point for the web application
│   ├── ...
├── tests/                     # Test cases for the application
│   ├── ...
├── setup.py                   # Setup script for installing the package
├── requirements.txt           # Dependencies for production
├── requirements-dev.txt       # Dependencies for development
├── README.md                  # This README file
├── CONTRIBUTING.md            # Contribution guidelines
├── SECURITY.md                # Security policy
└── .yamllint.yml              # YAML linting configuration
```

For further details on contributing, testing, and other resource links, please check the `CONTRIBUTING.md` and `SECURITY.md` files included in the project.

## Contribution
If you’d like to contribute to SearXNG, please read our [Contribution Guide](https://docs.searxng.org/dev/contribution_guide.html) for guidelines on how to get involved.

## Security
For reporting security issues, please follow the guidelines in the `SECURITY.md` file. Responsible disclosures are appreciated and will be handled swiftly.

---
Enjoy exploring and contributing to SearXNG! For more information, visit the [documentation](https://docs.searxng.org) or reach out to us at [contact@searxng.org](mailto:contact@searxng.org).