# rni - Package Manager

## Overview
`rni` is a simple package manager designed for installing, updating, and managing packages from GitHub and other sources. It allows users to easily fetch, install, and uninstall packages while maintaining version control.

## Installation
To install `rni`, run the following command:

```sh
pip3 install rni
```

## Usage
After installing `rni`, you can use the following commands:

### Install a Package
```sh
rni install <package_url>
```
Example:
```sh
rni install -git rasmnout/rni
```

### Update `rni`
```sh
rni update
```

### Remove a Package
```sh
rni remove <package_name>
```
Example:
```sh
rni remove example-package
```

### Search for a Package
```sh
rni search <package_url>
```
Example:
```sh
rni search -git rasmnout/rni
```

### List Installed Packages
```sh
rni list
```

## Features
- Install packages from GitHub and other repositories.
- Uninstall packages and clean up related files.
- Check and update installed packages.
- Maintain package logs for tracking installed software.

## Configuration
By default, `rni` modifies the system's `PATH` variable to include its `bin` directory:
```sh
export PATH="/rni/bin:/usr/local/bin:/bin:$PATH"
```
If this is not automatically set up, you may need to manually add it to your `~/.bashrc` or `~/.bash_profile`.

## Contributing
Feel free to contribute to `rni` by submitting pull requests on GitHub: [rni Repository](https://github.com/rasmnout/rni).

## License
`rni` is licensed under the Apache License 2.0.

## Contact
Author: trspn (Rasmnout Owner)  
Email: rasmnout@gmail.com  
Website: [rni Home Page](https://rasmnout.github.io/rni)

