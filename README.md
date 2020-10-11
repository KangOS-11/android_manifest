### Kang OS ###

![KangOS](https://i.ibb.co/Bg47twC/Pics-Art-10-11-01-40-57.jpg)
<p align="center">
</p>

# Initialize Local Repository #
```bash
repo init -u https://github.com/Corvus-R/android_manifest.git -b 11
```

# Or Initialize Shallow Clone #
```bash
repo init --depth=1 -u https://github.com/Corvus-R/android_manifest.git -b 11
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

# Building Environment #
```bash   
# Set up environment
. build/envsetup.sh

# Choose a target
lunch corvus_device-userdebug

# Build the ROM
make corvus
```

# Telegram Support 
[![Telegram](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/Telegram_button.png)](https://t.me/kangosop7p)

 Credits:
 =======

 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
 * [**Curvos-ROM**](https://github.com/Corvus-ROM)
 * [**AOKP**](https://github.com/AOKP)[AOKP The Original Masters of Kang]

For more detailed information visit [**here**](https://gerrit-review.googlesource.com/Documentation/intro-user.html)
