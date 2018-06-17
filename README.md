# LineageOS Source Device Tree Template

Start your Android career here. Build device trees and port custom ROMs and recoveries to new devices easily with this template.

Study the templates included to understand the file scheme, and then extract a boot or recovery image from your device, and run the mkvendor.sh script to make a preliminary tree. Here is Google's [AOSP tutorial](https://source.android.com/setup/develop/new-device) on how to make a device tree and another good explanation on [StackOverflow](https://stackoverflow.com/a/11353248) on what these files do.

You will need to add extra info (e.g. TARGET_BOARD_PLATFORM in [BoardConfig.mk](BoardConfig.mk.template)) before it is usable.
______

Last of all, have fun! Do some wonderful things with Android :)

Make sure to **cross-reference information** shown in tutorials you find with other device trees in the [LineageOS repositories](https://github.com/LineageOS?utf8=✓&q=android_device), **making sure not to add deprecated properties** or the like into your files, as the tutorials may be old.

You can build [TWRP](https://twrp.me/) (custom recovery) with your device trees. The official compilation tutorial can be found [here](https://forum.xda-developers.com/showthread.php?t=1943625) (tutorial by [@Dees-Troy](https://github.com/Dees-Troy) on XDA).

###### DISCLAIMER: This is all provided as-is. I am not responsible for any problems occurring upon use of the data provided or content referenced to in this repository.
