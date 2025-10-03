# PMD: SSS INSTALLATION INSTRUCTIONS
Thank you for choosing Pokémon Mystery Dungeon: Silver Saviors of the Sky (Henceforth "PMD: SSS") for your PMD hack experience! If you've played a PMD ROM hack before, the installation is the same as any other hack you've played. But, for the first-timers, who I know will be there, if you need any help, first check the [PMD Patching Guide](https://docs.google.com/document/d/1L67PlMxQ04Ns7pCRZJL3bhdWo1RLfq2NJP8t5z7985M/edit), or if you need further help go ahead and join my [Discord server](https://discord.gg/aEYSz2yXpm)! This is also the perfect place to chat with other players about PMD: SSS, whether you need any dungeon/tech help, or just want to chat!

If this is your first time patching a PMD ROM, please follow these instructions, ***after*** checking the hashes against the included Hashes.txt file to ensure that you got the files correctly:

- To install PMD: SSS you'll need to use a patcher application. The most common of these is a Windows app called [xDeltaUI](https://romhacking.net/utilities/598) but there are also (currently broken) online web patchers such as [Hack64](https://hack64.net/tools/patcher.php) that can do it or if you're technically savvy (which fortunately I am) there's also a version of xDelta that runs at the [command line](https://github.com/jmacd/xdelta) (which is the most up-to-date version, as it is the original) and many others.

- When you have found your patcher of choice, make sure you're in the mode where you're applying a patch and then input the following
	- For the patch location, select the .xdelta file in this folder that you are using, whether the base patch, or one of the emulator-specific patches.
	- For the location of the file to modify, select your ROM of Explorers of Sky. Please ensure that your ROM is for the USA version of the game and that it is a legally acquired copy of the game.
	- For the final parameter, select where you want to save the new file on your computer.
	- Xdelta CMD users: The full command (keeping the quotes, but replacing X:/path/to/clean.nds, X:/path/to/patch.xdelta, and X:/path/to/new.nds with the actual file path for each file, where X:/ is the Windows-exclusive letter of the drive where the files are stored. Note, not used in MacOS or Linux, just remove "X:", but not "/") is: xdelta3 -d -f -s "X:/path/to/clean.nds" "X:/path/to/patch.xdelta" "X:/path/to/new.nds" 
- If you are successful, you will have a new .nds file that can be played on a Nintendo DS emulator or real hardware (again, something I have the technical knowledge to know how to do)

- A common issue you may find is that you get a secondary compressor issue. This means the patcher you're using is not current enough to apply the latest .xdelta file types. You may need to update your application or find a different patcher. 

- If you get a checksum error when patching it means your ROM is not compatible with PMD: SSS, either because it's the EU ROM, it's the XenoPhobia version, or both. IT IS NOT RECOMMENDED TO SELECT ANY OPTIONS TO IGNORE CHECKSUMS IF THOSE OPTIONS ARE AVAILABLE TO YOU AS IT COULD LEAD TO UNEXPECTED BUGS IN-GAME. ***PLEASE CHECK YOUR ROM.***
