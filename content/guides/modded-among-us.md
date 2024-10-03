---
date: 2024-06-19T23:35:15.741Z
description: Guide walking through installing various mods for Among Us
link: false
categories: []
keywords: []
tags: []
title: How to Install Among Us Mods
show_lastmod: false
slug: modded-among-us
aliases:
  - /guides/town-of-us
  - /guides/the-other-roles
images:
  - /images/guides/modded-among-us/preview.png
preview: /images/guides/modded-among-us/preview.png
paige:
  toc: true
---


Follow the steps within to downgrade your *Among Us* to a compatible version and install various mods.

<!--more-->

## Downgrade your *Among Us* to the correct version

1. Open the Steam Console with: [steam://nav/console](steam://nav/console)

2. Run the following command to download *Among Us* **v2024.3.5**:

   ```bash
   download_depot 945360 945361 5073468987524498627
   ```

3. Once the download is complete, navigate to the folder where the files were downloaded, as shown in the Steam Console output

   ![Screenshot of the Steam Console with the download_depot command ran and the download location output.](/images/guides/modded-among-us/steam-console.png "Screenshot of the Steam Console with the download_depot command ran and the download location output.")

## *Town of Us*

{{<details-tag summary="Instructions (Deprecated)">}}

1. Copy the files from the *Among Us* download to a new location

   ![Screenshot showing copying Among Us game files between folders](/images/guides/modded-among-us/copy-game-files.png "Screenshot showing copying Among Us game files between folders")

2. Download the mod zip from [GitHub](https://github.com/eDonnes124/Town-Of-Us-R/releases/download/v5.0.4/ToU.v5.0.4.zip)

3. Extract the contents and move everything within to the same location you copied *Among Us* to above. Make sure you install this mod into a clean *Among Us* install.

   ![Screenshot showing moving mod files to the same folder as above](/images/guides/modded-among-us/move-mod-files.png "Screenshot showing moving mod files to the same folder as above")

4. Launch *Among Us*

   The last step is to just double-click the *Among Us* executable!

   > It may take up to 5 minutes for the first launch
   {.note}

{{</details-tag>}}

## *The Other Roles*

1. Copy the files from the *Among Us* download to a new location

   ![Screenshot showing copying Among Us game files between folders](/images/guides/modded-among-us/copy-game-files.png "Screenshot showing copying Among Us game files between folders")

2. Download the mod zip from [GitHub](https://github.com/tarper24/TheOtherRoles/releases/download/v4.6.0.24/TheOtherRoles.zip)

3. Extract the contents and move everything within to the same location you copied *Among Us* to above. Make sure you install this mod into a clean *Among Us* install.

   ![Screenshot showing moving mod files to the same folder as above](/images/guides/modded-among-us/move-mod-files.png "Screenshot showing moving mod files to the same folder as above")

4. Launch *Among Us*

   The last step is to just double-click the *Among Us* executable!

   > It may take up to 5 minutes for the first launch
   {.note}

## Troubleshooting and Issues

### Black Screen on Launch

If you are stuck on a black screen when launching, try the following:

1. Rename or Remove the `settings.amogus` file in `%APPDATA%\..\LocalLow\Innersloth\Among Us`

   > This will reset your game and lobby settings
   {.note}

   ![Screenshot showing a settings.amogus file and a settings.bak.amogus file](/images/guides/modded-among-us/rename-settings.png "Screenshot showing a settings.amogus file and a settings.bak.amogus file")

2. If you still get stuck on a black screen, you can try deleting the entire `Among Us` folder in `%APPDATA%\..\LocalLow\Innersloth\`

   > I recommend backing up your data before doing this
   {.warning}
