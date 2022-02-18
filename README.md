# remove_old_kernels

A BASH script for Ubuntu-based distributives that removes old linux kernels.

## Installation

Copy the `remove_old_kernels` file to `/usr/local/bin` and change its mode to `executable` (run the following commands as root or via sudo command):

```sh
mkdir -p /usr/local/bin
cp remove_old_kernels /usr/local/bin
chmod +x /usr/local/bin/remove_old_kernels
```

or call `install.sh` script from the repo (call `uninstall.sh` script to remove the script).

## Running

Call the script with the `-h` or `--help` flag to see help instructions:

```sh
remove_old_kernels --help
```

### Command line arguments

- `-d`, `--dry-run`     - only print packages
- `-t`, `--tools`       - remove HWE tools
- `-c`, `--cloud-tools` - remove HWE cloud tools
- `-v`, `--version`     - print the script version
- `-h`, `--help`        - show help information

## LICENSE

[LICENSE](./LICENSE) GPLv3.
