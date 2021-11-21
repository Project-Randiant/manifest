# Project Radiant #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/ProjectRadiant/manifest -b twelve

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags -v
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch radiant_$device-$type

# Build the code
$ mka bacon -j$
```

# Credits
* LineageOS for vendor and much more.
* ArrowOS who we track our hals from.
* ProtonAOSP for CTS and other patches.
* EvoX we also cherry-pick most stuff from them
* Also those forigners who help me and guide me else i am a jerk

# Features
* We have one monet app that is so sexy even oem are going to kang from us. also we jst tease little figma stuff though something i can't make it because i just need to show off what i can do. otherwise i am a 15 years old jerk i am an android developer in just 6-7 month easy you can also be just beg in front of pro forigners and learn from them see others code kang it just change little logic and most import is the trolling part troll people and jusr troll people. Because if you don't troll then it will not look good and people will not say that you are pro.


# Apply for Official # 
If you would like to apply for official, then feel free to take a look [here](https://github.com/ProjectRadiant/official_devices).