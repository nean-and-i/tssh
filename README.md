tssh
====

tmux based ssh clustershell

ssh is a small wrapper for tmux and developed to replaces cssh. With use of tmux “synchronize-panes” option input/commands can be broadcast to all panes.

debian based distros:

apt-get install tmux
prerequisits:

- default aspell dictionary ”/usr/share/dict/words” for random session names
- for ease of use hosts should be configured in ”./ssh/config”
