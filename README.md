# appify

Create a macOS Application from an executable (like a Go binary)

![Output of appify is a mac application](preview2.png)

* Create an Application from any executable
* Set your own logo
* Specify app metadata via flags


## Requires
Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Install go

```bash
brew install golang
```

## Install

To install `appify`:

~~go get github.com/machinebox/appify~~


```bash
go install github.com/machinebox/appify@latest
```
## Usage

```
appify -name "My Go Application" -icon ./icon.png /path/to/bin
```

It will create a macOS Application.

## What next?

If you want to build a Go backed web based desktop application, check out our [machinebox/desktop](https://github.com/machinebox/desktop) project.
