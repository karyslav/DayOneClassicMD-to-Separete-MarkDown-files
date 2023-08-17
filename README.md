# DayOneClassicMD-to-Separete-MarkDown-files
Convert Day One Classic MD export to Obsidian

This script is intended for OLD version of DayOne classic which can export single MerkDown file. In my example it is DayOne Classic version 1.10.6.

Instructions to integrate the script as a right-click service on macOS:

1. Open the Automator app on your Mac.
2. Choose File > New and select Quick Action.
3. At the top, set the service to receive selected files or folders in Finder.
4. Drag the Run AppleScript action to the workflow area.
5. Replace the default AppleScript in the action with the script provided in repo.
6. Save the service with a name like "Convert Day One Classic MD export to Obsidian".

Now, when you right-click a file in Finder, you should see the "Convert Day One Classic MD export to Obsidian" option in the context menu under Services.
When you use this service on a file, it will process the file as described and save the entries in an "export" folder in the same directory as the file. If you run the service on the file again, it will update any changed entries and skip unchanged ones.

If you export the file from DayOne again, and place it in the same folder, run the export again, only changed and new entries will be added.

Filename of every item starts with time and date of creation, it is also set up as date of ceration of the file, followed by hash definig its contents (if there is a change).

Whole script is provided as it is, no guarantees given. I just want to make it public if anyone find it useful.
