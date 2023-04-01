# 📦 https://vpm.razgriz.one/ 📥

![GitHub deployments](https://img.shields.io/github/actions/workflow/status/vrchat-community/template-package-listing/build-listing.yml?label=Build%20Package%20Listing)

This repository hosts my [VPM](https://vcc.docs.vrchat.com/vpm/)-Compatible packages for use with the [VRChat Creator Companion](https://vcc.docs.vrchat.com/).

## Usage With VCC
### Adding Repo Listing
- If you're reading this after VCC 2.1.0 has been released (hopefully by April 8, 2023), just go to https://vpm.razgriz.one/, click `Add to VCC`, and follow the prompts.
- Otherwise, make sure you have the [VPM CLI](https://vcc.docs.vrchat.com/vpm/cli) installed, then run the command `vpm add repo https://vpm.razgriz.one/index.json`.

### Adding Packages to a Project

In the VPM Interface, select your project, locate the `Selected Repos` dropdown, and check `Raz's VPM Repo`. Then, select the package you want to add, and click the plus button.

## Manual Usage

Each package has its own repository, and usually contains a standalone package distribution, as well as a VPM-compatible package distribution. If you want to use the standalone package, you can download it from the releases page of the package's repository.