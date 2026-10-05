# MindTheGapps Lite

**A lightweight Google Apps package for Android devices.**

This checkout currently provides arm64 builds.

## Build a standalone ZIP

From the repository root, run make distclean and make gapps_arm64.

The signed package is written under out/.

## Build inline with Android

1. Sync this repository to the path stored in $GAPPS_PATH.
2. Include $GAPPS_PATH/arm64/arm64-vendor.mk from the product makefile.

## Included components

- Google Play Store (Phonesky)
- Google Play services system APEX
- Google Services Framework
- Google Calendar and Contacts sync adapters
- Google LatinIME support library

Thanks and Credits
-------------------

aleasto
- Install scripts for 11 with dedicated partitions support

cdesai
- Reminding me that /proc/meminfo is a thing

ciwrl
- Catching a few spelling errors in this file

gmrt
- Initial list for gapps

flex1911, raymanfx, deadman96385, jrior001, haggertk, arco
- Thorough testing

harryyoud
- Thorough testing and Jenkins setup

haggertk
- Suggesting CI integration of privapp-permissions

jrizzoli
- Initial build scripts and build system

luca020400
- Fixing my makefiles

LuK1337
- Setting up custom Docker image for CI, improving scripts, thorough testing

mikeioannina
- The name for MindTheGapps

aleasto, razorloves, raymanfx
- Helping maintain this repo

syphyr
- Showing me how to repack libs in PrebuiltGmsCore
