# dev-tools
### A small collection of automation scripts useful for repetitive & tedious tasks.

> Begin by cloning repo to desired location.

## bash scripts

- *push* - Adds and pushes ONLY SELECTED files to github.
> Copy to `/bin/` directory to use it globally by using its filename. `sudo cp push /bin/push`

    - Checks if git credentials are set.
    - Asks user for commit message.
    - Asks for confirmation before pushing.
    - Displays git errors and hides git success messages.
- *pushall* - Adds and Pushes ALL files/changes to github.
> Copy to `/bin/` directory to use it globally by using its filename. `sudo cp pushall /bin/pushall`

    - Checks if git credentials are set.
    - Asks user for commit message.
    - Asks for confirmation before pushing.
    - Displays git errors and hides git success messages.
