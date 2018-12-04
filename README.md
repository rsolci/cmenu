# CMENU
A simple customizable bash menu

Usage: `./cmenu.sh your_properties_file.properties`

Properties file:
- Follow `name=value` pattern
- Must end with a new line (have to fix this)
- Property names can not contain spaces.
- Dots in property name will be replaced by undescore `_`

You can create an alias for a more convinient way to use: `alias myVpns="/path/to/cmenu.sh /path/to/vpns.properties"`

This way you can call just `myVpns` in your terminal.

To exit, just press `Ctrl+C`