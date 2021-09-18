## Downloads (macOS)

- The latest release of [checkra1n](https://checkra.in)
- The custom version of [pongoOS](https://github.com/checkra1n/BugTracker/files/6429930/Pongo.zip)

![]({{ "/assets/images/checkra1n.png" | absolute_url }})

## Installing checkra1n

If you're using an M1 Mac, you will be prompted during the process to unplug and replug the device and will need to do so.
{: .notice--info}

1. Open the `pongoOS.zip` file, navigate to `PongoConsolidated.bin`, then extract it.
  - Keep note of where you extract this
1. Open a terminal and run checkra1n in CLI mode by using `/Applications/checkra1n.app/Contents/MacOS/checkra1n -c -k [path to PongoConsolidated.bin]`
1. Plug your iOS device into your computer
1. You will now be presented with instructions in how to reboot your device into [DFU mode](faq#dfu_mode), enter DFU mode to begin
  - Follow the instructions until your device shows a black screen
1. After this, checkra1n should automatically install

Your iOS device should now reboot.

To install Odysseyra1n, <u>do not</u> open the checkra1n app and install Cydia. Instead, follow the following instructions to install Sileo.

## The Odysseyra1n script

1. Open the terminal app on your computer
1. Ensure that your computer is trusted by your device
1. Install "homebrew" by pasting and executing the following command:

    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
1. Install "iproxy" by pasting and executing the following command:

    `brew install libusbmuxd`
1. Install the Odysseyra1n script by pasting and executing the following command:

    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/coolstar/Odyssey-bootstrap/master/procursus-deploy-linux-macos.sh)"`

{% include_relative include/end-of-page.md %}