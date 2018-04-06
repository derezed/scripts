# iOS Simulator Script

Boot specific iOS devices from command line with or without a URL to be opened in Safari upon boot.

## Requirements

* Update to date version of xCode installed (run xCode after installation to insure all other packages are downloaded and setup)

### Usage
In a terminal window navigate to where the scripts are installed. Once in the proper location run the script using the following command:

`./ios-simulator`

The script has 3 potential arguments:

* -d | --device: The device to boot. Currently accepts the following:
  - ipad-pro
  - ipad
  - iphone-x
  - iphone-se
  - Ex: `./ios-simulator -d ipad-pro` or `./ios-simulator --device ipad-pro`
* -u | --url: The URL to open in Safari after the device has finished booting. Can be any URL (local or external).
    - Ex: `./ios-simulator -d ipad-pro -u https://www.google.com`
