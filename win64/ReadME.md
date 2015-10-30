This is not an installer file of BitcoinDark Desktop App for windows. Instead it's just Executable portable BitcoinDark zipped in archive.

Just unzip the zip file, and execute the `BitcoinDark.exe` file in there.

Please do not delete any other files in that folder which are sitting besides `BitcoinDark.exe`. Those are all needed by this desktop app.

For starting BitcoinDark takes a little time, as it's all packaged in this single binary file.
The executable file runs in background for few seconds while it extracts all the desktop app files in `%tmp%` directory of windows, and then shows the Desktop App window.

If you are running this BitcoinDark wallet first time on your windows, that probably will take a bit of time setting up it's default BitcoinDark.conf file under `%AppData%/BitcoinDark/BitcoinDark.conf`.
Wait for a minute or so, and keep an eye on `Windows Task Manager`'s processes tab. It must be showing your `BitcoinDarkd.exe` process running there. You might see `BitcoinDark.exe` and `BitcoinDarkd.exe` in processes.

If you can't find it there, that means either BitcoinDarkd.exe is crashed or it's ended due to something wrong with either BitcoinDark.conf file or SuperNET.conf file.

If you want to have some custom settings in your `SuperNET.conf` file, make that `SuperNET.conf` file and place it anywhere on system.

For example we placed it just placed it under `C:\SuperNET.conf` location on windows.

Now to make BitcoinDark Desktop App pick these settings you need to specify this SuperNET.conf file's path in BitcoinDark.conf file which is located at `%AppData%/BitcoinDark/`.

Open the file `%AppData%/BitcoinDark/BitcoinDark.conf` and place the path of your SuperNET.conf file in it as per following example:

`SuperNET=C:/SuperNET.conf`

Note that in BitcoinDark.conf file you will only use this slash `/`, and not `\` slash.

Also note that you do not need to put either `"` or `'` in any setting in BitcoinDark.conf file.

Any issues, report it in #btcd channel on SuperNET Slack. Get invite by going to supernet.org
