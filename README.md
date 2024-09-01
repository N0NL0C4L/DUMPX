# DUMPX

DUMPX is a Python script designed to automate the process of scanning various environment paths on a web server to uncover exposed `.env` files and configurations. This can be an invaluable tool for cybersecurity professionals and developers to identify potential security misconfigurations and vulnerabilities.

## Features

- **800+ Environment Paths**: Automatically scans over 800 common and obscure paths to find exposed environment files.
- **Multi-threading Support**: Uses Python's multiprocessing to speed up the scanning process by utilizing multiple threads.
- **User-friendly Output**: Displays results in a clear format and saves findings to a text file for further analysis.
- **Automatic Dependency Installation**: Automatically installs missing dependencies on the first run.

## Requirements

- Python 3.x
- Required Python packages: `requests`, `fake_headers`, `colorama`

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/N0NL0C4L/DUMPX.git
    cd DUMPX
    ```

2. Run the script:
    ```
    python3 dumpx.py
    ```

3. Follow the on-screen prompts to provide a list of websites and the number of threads to use.

## Usage

- Prepare a text file with a list of websites you want to scan.
- Run `dumpx.py` and provide the path to the file and the desired number of threads.

## Disclaimer

DUMPX is intended for educational purposes and security testing in authorized environments. The author is not responsible for any misuse or damage caused by this tool.

## Author

- Developed by [N0NL0C4L](https://github.com/N0NL0C4L)
