# .bash_profile

[ -f "$HOME/.bashrc" ] && . "$HOME/.bashrc"

if [ "$(tty)" == "/dev/tty1" ]; then 
	command -v sway && dbus-run-session sway
fi
