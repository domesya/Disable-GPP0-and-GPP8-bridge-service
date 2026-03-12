# Disable GPP0 and GPP8 bridge service
This is a systemd service file meant to be put in /etc/systemd/system/ folder. Just put it there, enable it and it should work on most systemd distros. Disabling those bridges is meant to make suspend work as intended on systems wit B550 motherboards.
