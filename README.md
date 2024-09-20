# finder-sync-extension-crash-reproduction

This reproduction showcases an issue with the Finder Sync Extension. When using Swift 6 with macOS Sequoia and executing an action (either toolbar or context menu) the extension crashes.

The project consists of a base macOS project with an added finder sync extension (no changes made to generated sample code).

The crash log can be found in the file `crash-log.ips`
