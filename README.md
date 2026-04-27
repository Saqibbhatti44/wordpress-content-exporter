# WordPress Content Exporter

This Python script extracts post/page titles, excerpts, main content, and PDF attachment links from a WordPress XML export and saves them to Excel and Word files.

## Features
- Extracts Gutenberg/ACF block content
- Handles post titles, excerpts, and PDF attachments
- Outputs to Excel and Word

## Usage
1. Place your `wordpress-export.xml` in the same folder as the script.
2. Run:

3. Check the generated `website_content.xlsx` and `website_content.docx`.

## Requirements
- Python 3.x
- pandas
- python-docx
- beautifulsoup4

## License
MIT