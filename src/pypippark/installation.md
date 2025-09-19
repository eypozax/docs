# Installation

There are different methods to install **PyPipPark** on your device:

## Method 1: Install via Debian `.deb` package

1. From the latest release, download the file ending with `.deb` from:  
[PyPipPark Releases](https://github.com/eypozax/pypippark/releases/)

2. Install the `.deb` file. You have two options:

* **Graphical installation:** Right-click the downloaded file and select **Install**.  
* **Command line installation:** Open a terminal and run:

```bash
# Needs sudo permission
sudo dpkg -i path/to/downloaded/file.deb
```

---

## Method 2: Direct installation of the binary

1. Download the latest release file from GitHub:
   [PyPipPark Releases](https://github.com/eypozax/pypippark/releases/)

2. Move the downloaded binary to `/usr/local/bin`:

```bash
# Needs sudo permission
sudo cp path/to/downloaded/file /usr/local/bin

# Make sure the binary is executable (if needed)
sudo chmod +x /usr/local/bin/pypippark
```
