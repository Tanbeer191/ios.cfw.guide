## Downloads (Linux)

- The latest release of [checkra1n](https://checkra.in)
  - If you are on an A9X device, you should instead get the 0.12.2 release of [checkra1n](https://checkra.in/releases/0.12.2-beta#all-downloads)

![]({{ "/assets/images/checkra1n.png" | absolute_url }})

## Installing checkra1n

1. Run the `checkra1n` binary in the terminal using `./checkra1n`
  - You may need to run `sudo chmod a+x ./checkra1n` if the binary doesn't run
  - If you're on A11, you will need to head into `Options`, then enable the `Skip A11 BPR Check` option once it runs
  - If you're on A9X and are on iOS 14.4 to 14.4.2, you will need to head into `Options`, then enable the `Allow Untested Versions` option once it runs
1. Click `Start` and follow all onscreen prompts
1. You will now be presented with instructions in how to reboot your device into [DFU mode](faq#dfu_mode), click `Start` to begin
  - Follow the instructions until your device shows a black screen
1. After this, checkra1n should automatically install

Your iOS device should now reboot.

To install Odysseyra1n, <u>do not</u> open the checkra1n app and install Cydia. Instead, follow the following instructions to install Sileo.

## The Odysseyra1n script

1. Open the terminal app on your computer
1. Ensure that your computer is trusted by your device
1. Install "iproxy" by pasting and executing the following command:
  - Ubuntu/Debian: `sudo apt install libusbmuxd-tools`
1. Install the Odysseyra1n script by pasting and executing the following command:

    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/coolstar/Odyssey-bootstrap/master/procursus-deploy-linux-macos.sh)"`

1. Sileo should install to your device
1. Open Sileo, navigate to Search and search for "libhooker"
1. Press "Confirm", then once it finishes, press "Restart Springboard."
1. Wait for your device to respring

{% include_relative include/end-of-page.md %}
