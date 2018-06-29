# SDFile Updater

A homebrew application for the Nintendo Switch that will connect to a SDFile Updater Server and update your SDFiles automatically.

## settings.cfg

| Config option                             | Description
| ----------------------------------------- | ---
| `host = "http://sdfu.stevenmattera.com";` | Which server to connect to. You can host your own server using the files in the [server repository](https://github.com/StevenMattera/SDFileUpdaterServer).
| `channel = "stable";`                     | Stable (*stable*) will download the latest tag and bleeding edge (*bleeding-edge*) will download the latest commit.
| `version = "";`                           | The version that is currently installed on your SD card.
| `launcher = "hekate";`                    | Hekate (*hekate*) will use the hekate files and Switchblade (*switchblade*) will use the switchblad files.

## Credits

* Thanks to tumGER for maintaing the SDFilesSwitch repo, without that repository this application wouldn't exist.
* Thanks to vgmoose for examples on using minizip in appstorenx.
* Thanks to y4my4m and natinusala in the ReSwitched discord for their discussions around libcurl.