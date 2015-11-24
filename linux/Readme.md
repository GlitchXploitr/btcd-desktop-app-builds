The Installer file is named with the Date and Time it compiles.

Usage: BitcoinDarkInstaller-YYYY-MM-DD-xxxxxxxxx.run [OPTION...]

Example:

  `sh BitcoinDarkInstaller-YYYY-MM-DD-xxxxxxxxx -install`		  # To Install BitcoinDark on system
  
  `sh BitcoinDarkInstaller-YYYY-MM-DD-xxxxxxxxx -uninstall`		# To Uninstall BitcoinDark on system

Options:

  `-install`			: To install BitcoinDark.
  
  `-uninstall`		: To uninstall BitcoinDark.
  
  `-help`				  : To see this help.

- The installer puts Bitcoindark wallet files in `/opt/BTCDWallet/`
- Creates a binary link at `/usr/bin/` of `btcdwallet`. Means you can also execute the command `btcdwallet` in terminal to open desktop app of Bitcoindark.

After installation you can find the Bitcoindark Wallet in Applications menu on system. Can search it with `btcd` in ubuntu applications launcher to open the desktop app. It's that easy.

If you do not trust the installer file, you can make it yourself using the shell script `btcdlinuxbuild.sh` listed here: https://github.com/satindergrewal/SuperMesh/tree/alpha-0.0.1e/Old%20Configs%20%26%20Scripts/scripts/btcd-build-scripts

