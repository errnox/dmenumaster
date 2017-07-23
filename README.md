# `dmenumaster`: A Command Runner Hotlist

This script

1. reads a list of commands from the file `$HOME/.bash/commands` (one command per line),
2. interactively prompts you for one of those commands using `dmenu`,
3. executes the user-selected command and
4. promotes the this command to the top of the command list by rewriting `$HOME/.bash/commans`.

As a result, you can

- repeat the last command by simply selecting the first one in the list or
- select one of the recently selected commands from the top of the list.

*Disclaimer:* There is no "frecency" ordering going on. Recency is the only reordering factor.

Requirement: `dmenu` has to be installed on the system.
