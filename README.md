# DayOneClassicMD-to-Separete-MarkDown-files
Convert Day One Classic MD export to Obsidian

Instructions to integrate the script as a right-click service on macOS:

1. Open the Automator app on your Mac.
2. Choose File > New and select Service.
3. At the top, set the service to receive selected files or folders in Finder.
4. Drag the Run AppleScript action to the workflow area.
5. Replace the default AppleScript in the action with the script provided above.
6. Save the service with a name like "Split Markdown Entries".

Now, when you right-click a file in Finder, you should see the "Split Markdown Entries" option in the context menu under Services.
When you use this service on a file, it will process the file as described and save the entries in an "export" folder in the same directory as the file. If you run the service on the file again, it will update any changed entries and skip unchanged ones.
