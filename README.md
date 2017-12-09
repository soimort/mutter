# Meine Mutter

Mort's fork of [Mutter](https://git.gnome.org/browse/mutter), GNOME's window manager.

Personal tweaks:

1. Do NOT raise the entire tiling group when raising a single window. (Revert [e76a0f5](https://github.com/GNOME/mutter/commit/e76a0f564c1e07e32fe857d0f8e5b723c3bbe57d#diff-029d285c3238fbe60d57f513265e1723))
2. Do NOT complain about a client sending _`NET_ACTIVE_WINDOW` with timestamp 0. (Because tint2 does that and it spams my journal too much.)
