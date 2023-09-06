# vscode-env-debug

A VSCode project for debugging Code's executable launch environment variables.
The included `launch.json` Debug task prints the VSCode process' environment
variables: `PATH`, and `SSH_AUTH_SOCK`.  This should assist with plugins which
rely on environment variables being set, such as the Git plugin using SSH agent
authentication.

## Requirements

- Visual Studio Code

## Usage

- Open the `.vscode/vscode-env-debug.project-workspace` using VSCode / Code OSS.
- Open the "`Run and Debug`" pane (<kbd>Ctrl</kbd>`+`<kbd>Shift</kbd>`+`<kbd>X</kbd>)
- Select the "`Debug VSCode env`" launch task
- Click "`Start Debugging`" or press <kbd>F5</kbd> to run the task
- Check the output in the '`Debug Console`"

