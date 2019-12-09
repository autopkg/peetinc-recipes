# Orchard_Grove

There are PREINSTALL and POSTINSTALL script variables enabled in this recipe. Most of the ways to deploy NoMAD AD Login needs a pre and/or post install script. If you're using profiles to configure the settings, disable or ignore the default scripts.

My hope is to make this as easy as possible to use for the most folks. To that end, there's an NoMADLoginAD.png in this repo. The package itself is icon free.

This download recipe differs from the ones in bochoven-recipes in the following ways:
- This one performs code signature verification.
- This one acquires just the latest version NoMAD Login AD pkg.
- This one adds check phase
