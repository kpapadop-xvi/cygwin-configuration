# cygwin-configuration

Preferences, scripts and aliases useful with Cygwin

## Aliases

Add (or uncomment) the following in `~/.bashrc`

```bash
if [ -f "${HOME}/.bash_aliases" ]; then
  source "${HOME}/.bash_aliases"
fi
```

# Terminal Minimal Style

If using MinTTY, copying the file `.minttyrc` to the user's home directory
will configure the terminal window to:

- Be transparent.
- Maximinze the window.
- Hide the scrollbars.
- Copy selections as plain text.

Copy (or merge the contents of) the file `.bash_aliases`

## Word Navigation (CTRL + Left/Right Arrows)

 Add the following at the end of `~/.inputrc`

```text
# CTRL + Left/Right Arrows
"\e[1;5D": backward-word # Left
"\e[1;5C": forward-word # Right
```
