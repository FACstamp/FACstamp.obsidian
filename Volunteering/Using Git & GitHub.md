Note - this page needs more work.

As described in more detail in [[Using Obsidian]], this website is an Obsidian vault stored in Git and hosted in [GitHub](https://github.com/FACstamp/FACstamp.obsidian).  The current thought is to use GitHub for collaboration and development.  GitHub will be/is leveraged to  start [discussions](https://docs.github.com/en/discussions) and submit [issues](https://docs.github.com/en/issues) and [pull requests](https://docs.github.com/en/pull-requests), etc.

The following are some notes regarding collaboration and shared development:

1) The GitHub/Git landing page is [README.md](README) while the end-user (Obsidian based) landing page is [Welcome.md](Welcome.md).
2) As an Obsidian vault, Obsidian wants to manage its own files and directories.  Without a subscription fee, the native Obsidian vault syncing is disabled, and on MacOS Obsidian places them in "/Users/\<user>/Library/Mobile Documents/iCloud~md~obsidian/Documents/\<vault.>/"..  With Apple iCloud third-party syncing, placing the .git directory in this tree can cause issues.  As such, one work around is to place the .git directory outside the Obsidian managed tree (either in or outside of iCloud) via the git clone "--separate-git-dir" switch.  If you clone this repo into an iCloud or other third-party syncing solution, you may need to place the .git directory outside that area.
3) This Git repository uses Git LFS to store all images, currently located in the Attachments folder.  See [About large files on GitHub](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github) (and/or if necessary, [Git LFS Storage](https://git-lfs.com/).
