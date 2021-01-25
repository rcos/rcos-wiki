# Tmux

**Website**: <https://tmux.github.io/>

Tmux is a terminal multiplexer. It essentially allows one to have
multiple virtual terminal sessions (Tmux sessions) running in one
terminal window. Tmux sessions are not bounded by a physical terminal
window. This introduces convenient features such as:

-   Splitting (vertically or horizontally) two Tmux sessions in one
    physical terminal window.
-   Attaching/detaching Tmux sessions (for running something in the
    background, such as an SSH connection).
-   Moving Tmux sessions from one physical terminal window to another.
-   Being able to display a Tmux session in multiple physical terminal
    windows.

## Installation

On Unix-like systems, tmux should be installed through your system\'s
package manager (apt, yum, pacman, etc).

## Usage

Tmux is mostly used through keyboard shortcuts. Most keyboard shortcuts
involve use of a user define \"Leader\" key, which is `Ctrl-b` by
default, followed by the command itself. E.g. `Ctrl-b+%` to vertically
split a window.

All keyboard shortcuts, as well as the leader key, can be configured
through the Tmux config file.

## Cofiguration

Tmux is configured through a configuration file. There is a per-user one
located at `~/.tmux.conf`, while a global system one exists in
`/etc/tmux.conf`.

## Resources

For a great general overview and configuration tutorial, check out the
[Arch Linux wiki page](https://wiki.archlinux.org/index.php/Tmux).

There are also community made [cheat
sheets](https://tmuxcheatsheet.com/) and the Tmux
[manpage](https://man.openbsd.org/OpenBSD-current/man1/tmux.1), which
explain what each keyboard shortcut does.

[Here](https://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/)
is a blog post someone made on how they configured Tmux. This can be
used as a great starting point, and can give you a general sense on how
to configure Tmux yourself.
