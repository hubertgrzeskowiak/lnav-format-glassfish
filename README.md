# lnav-format-glassfish
LNAV formatter for Glassfish log files.

When using the default Logger in Glassfish and Payara, the LNAV java format doesn't match. This is an extension of that matcher that adds a new pattern and the alert-level SEVERE.

In order to use simply put the json file somewhere inside your `~/.lnav/formats/installed/` or `~/.lnav/formats/default/`.
