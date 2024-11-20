# Responsible Terminal Logging

## What is .zshrc?

The .zshrc file is a configuration file for the Z shell (zsh), a powerful and customizable Unix shell. This file is executed every time a new zsh session starts, allowing users to set environment variables, define aliases, configure shell options, and customize the shell prompt. Essentially, it helps tailor the shell environment to the user's preferences and workflow.

## What is this .zshrc file?

This zshrc file is based on the original kali zshrc file but displays the current time and date and starts a terminal logging script for every new terminal opened. This is useful for red teaming operations as this provides
- timestamped actions
- comprehensive logging
- accountability and transparency
- easy evidence collection

## How to use this?
- In the /home/kali directory, remove the file .zshrc file
- Download this .zshrc file and place it in the /home/kali directory
- Run `source .zshrc`

# Kudos 
This is all based of the Responsible Red Teaming course from The Taggart Institute
