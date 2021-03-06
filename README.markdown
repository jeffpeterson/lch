# lch – launchctl helper

`lch` is a small tool for easily managing LaunchAgents.

## Usage

    lch list          - list agents installed by lch
    lch load <name>   - load an agent installed by lch
    lch unload <name> - unload an agent installed by lch
    lch reload <name> - reload an agent installed by lch

    lch start <name> - start a loaded agent
    lch stop <name>  - stop a loaded agent

    lch brew <name>   - load an agent from an homebrew formula and tell it not to start at boot
    lch unbrew <name> - unload agent from an homebrew formula

    lch cat <name>  - show plist of agent
    lch edit <name> - edit an agent's plist
    lch new <name>  - create an empty agent
    lch rm <name>   - remove an agent installed by lch

    lch add <name> <key> <type> <value> - add a key to an agent's plist
    lch set <name> <key> <value>        - set a key in an agent's plist


## Example

    brew install postgresql
    lch brew postgresql
    lch start postgresql
