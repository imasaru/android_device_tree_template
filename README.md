# LineageOS Source Device Tree Template

Start your Android career here. Build device trees and port custom ROMs and recoveries to new devices easily with this template.

Study the templates included to understand the file scheme, and then extract a boot or recovery image from your device, and run the mkvendor.sh script to make a preliminary tree. Here is a good explanation on [StackOverflow](https://stackoverflow.com/a/11353248) on what these files do. 

You will need to add extra info (e.g. TARGET_BOARD_PLATFORM in [BoardConfig.mk](BoardConfig.mk.template) before it is usable.
______

Last of all, have fun! Do some wonderful things with Android :) Who knows where it'll lead (only you!)


Personally, I started [here](https://developerswork.github.io/works/GUIDES/AndrodDeviceTree/#). Be warned that this is an **old tutorial**, so when using it, be sure to **cross-reference information** shown in the tutorial with the templates here (they are new as of August 2017), or other device trees in the [LineageOS repositories](https://github.com/LineageOS?utf8=✓&q=android_device), **making sure not to add deprecated properties** or anything like that into your device files. The tutorial is perfectly usable, though.

Maybe we can encourage [@DevelopersWork](https://github.com/DevelopersWork) to update his tutorial :wink:

You can build [TWRP](https://twrp.me/) (custom recovery) with your device trees, as well. The official compilation tutorial can be found [here](https://forum.xda-developers.com/showthread.php?t=1943625) (tutorial by [@Dees-Troy](https://github.com/Dees-Troy) on XDA).

###### DISCLAIMER: This is all provided as-is. I am not responsible for any problems occurring upon use of the data provided or content referenced to in this repository.
