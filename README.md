# Terminal Search: Web Search and Navigation Tool

This Python script allows you to perform web searches using the Brave search engine and navigate to the selected search results using the command line. It utilizes BeautifulSoup for web scraping and fzf for interactive selection.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/MidhunManu/terminal-search
    cd terminal-search
    ```

2. Install the required dependencies:

    ```bash
    pip install beautifulsoup4 requests
    ```

3. Make the script executable:

    ```bash
    chmod +x tsearch
    ```

## Usage

To use the tool, simply run the script with a search query as an argument:

```bash
./tsearch "your search query"
