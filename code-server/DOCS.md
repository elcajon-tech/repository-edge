# Home Assistant Add-on: Studio Code Server

This add-on runs Studio Code Server, allowing you to edit your Home Assistant
configuration directly from your web browser and can be embedded straight
into the Home Assistant frontend UI.

Visual Studio Code runs as a remote server using `code-server`, and is a
fully fledged VSCode experience.

The add-on has the Home Assistant, MDI icons and YAML extensions pre-installed
and pre-configured right out of the box. This means that auto-completion works
instantly, without the need for configuring anything.

## Installation

The installation of this add-on is pretty straightforward and not different in
comparison to installing any other Home Assistant add-on.

1. Add the repository
1. Install the add-on
1. Start the add-on
1. Click the "OPEN WEB UI" button to open Visual Studio Code.

## Configuration

**Note**: _Remember to restart the add-on when the configuration is changed._

**Note**: _This is just an example, don't copy and paste it! Create your own!_

### Option: `log_level`

The `log_level` option controls the level of log output by the addon and can
be changed to be more or less verbose, which might be useful when you are
dealing with an unknown issue. Possible values are:

- `trace`: Show every detail, like all called internal functions.
- `debug`: Shows detailed debug information.
- `info`: Normal (usually) interesting events.
- `warning`: Exceptional occurrences that are not errors.
- `error`: Runtime errors that do not require immediate action.
- `fatal`: Something went terribly wrong. Add-on becomes unusable.

Please note that each level automatically includes log messages from a
more severe level, e.g., `debug` also shows `info` messages. By default,
the `log_level` is set to `info`, which is the recommended setting unless
you are troubleshooting.

### Option: `init_path`

The `init_path` option allows to change the path containing the custom
init scripts and services. The default value is `/share` which is leading to
`/share/vscode/{cont-init.d,services.d}`.

## Resetting your VSCode settings to the add-on defaults

The add-on updates your settings to be optimized for use with Home Assistant.
As soon as you change a setting, the add-on will stop doing that since it
might be destructive. However, in case you changed some things, but want to
return to the defaults as delivered by this add-on, do the following:

1. Open the Visual Studio Code editor.
1. Click on `Terminal` in the top menu bar and clik on `New Terminal`.
1. Execute the following command in the terminal window: `reset-settings`.
1. Done!