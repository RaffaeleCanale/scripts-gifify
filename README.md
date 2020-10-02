### Easily manage downloaded files

# Installation

Installation requires [`wx-pm`](https://github.com/RaffaeleCanale/wx-pm)

`cd` to the project directory and run:
```
wx install
```

# Configuration

In `config.properties`, set the `__DOWNLOADS_DIR__` property with the path of your downloads directory.

# Usage

```
downloads <operation> </count>
```
Where operation is one of:
```
copy, move, open, list
```

# Examples
```sh
downloads move -3 # Move the last 3 downloaded files to the current directory

downloads open    # Open the last downloaded file

downloads list    # List the last downloaded files
```
