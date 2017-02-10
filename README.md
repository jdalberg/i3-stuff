Some stuff from Arch Linux and i3 on my macbookpro11,5

20-display.rules - A rule to capture events from my display driver
hot_plug.service - A systemd service to one-shot start the set_workspaces script,
                   this runs when the rule above fires.
set_workspaces   - A shell script that does the workspace shuffling depending on
                   the connected displays.
