# dev-tools
### A small collection of automation scripts useful for repetitive & tedious tasks.

- Begin by cloning repo to desired location.
- Follow individual instructions as per script.

## bash scripts

1. `push` - Adds and pushes ONLY SELECTED files to github.
> Copy to `/bin/` directory to use it from any directory: `sudo cp push /bin/push`
> > Repeat this command after an update.
- To use it type its name then names of files to push: `push README.md .gitigore`

    - Checks if git credentials are set.
    - Asks user for commit message.
    - Asks for confirmation before pushing.
    - Displays git errors and hides git success messages.
    - Accepts -f command.
---
2. `pushall` - Adds and Pushes ALL files/changes to github.
> Copy to `/bin/` directory to use it from any directory `sudo cp pushall /bin/pushall`
> > Repeat this command after an update.
- To use it type its name: `pushall`

    - Checks if git credentials are set.
    - Asks user for commit message.
    - Asks for confirmation before pushing.
    - Displays git errors and hides git success messages.
    - Accepts -f command.
---
## LAST UPDATE 23RD MARCH 2023
