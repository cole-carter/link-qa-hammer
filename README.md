# Link QA Hammer

An automated tool for verifying and categorizing backlinks for SEO purposes. Integrates with Screaming Frog SEO Spider and Ahrefs for comprehensive link analysis.

## Development Setup

1. Clone the repository:
```bash
git clone https://github.com/cole-carter/link-qa-hammer.git
cd link-qa-hammer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the tool:
```bash
python src/main.py
```

## Project Structure

- `src/`: Source code
  - `main.py`: Entry point
  - `core/`: Core functionality
  - `utils/`: Utility functions
- `tests/`: Test files
- `.config/`: Configuration files
- `stories/`: Story data directories
- `logs/`: Log files
- `build_scripts/`: Build and deployment scripts

## Building

To create an executable:
```bash
python build_scripts/build.py
```