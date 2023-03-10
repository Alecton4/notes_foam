# openSUSE Tumbleweed (20230128) Installation

## Before installation

Download the ISO image from [the official site]( https://get.opensuse.org/tumbleweed/#download ).

## During installation

Refer to [the official Leap startup guide]( https://doc.opensuse.org/documentation/leap/startup/html/book-startup/art-opensuse-installquick.html#sec-opensuse-installquick-install ) and [the community guide]( https://opensuse.github.io/openSUSE-docs-revamped-temp/yast_installer/ ) for more. Below are a few notable points.

### Network settings

- Do **not** configure WiFi during installation.

### Disk

Refer to [the community guide]( https://opensuse.github.io/openSUSE-docs-revamped-temp/yast_installer/#about-partition-schemes ) for more. Below is my configuration:

- Use the bootloader from Windows which will be `/boot/efi`.
- A new separate partition for `/`.
- A new separate partition for `/home`.
- A new separate partition for `swap` which size supports hibernation.

### Installation settings

- No need to install many packages during installation. We can install them later.

## After installation

See [[Tumbleweed/tweak]] for more tweaks after installation.

[//begin]: # "Autogenerated link references for markdown compatibility"
[Tumbleweed/tweak]: tweak.md "openSUSE Tumbleweed Tweak"
[//end]: # "Autogenerated link references"
