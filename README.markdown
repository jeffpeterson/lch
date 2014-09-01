# lch – launchctl helper

`lch` is a small bash script that makes managing LaunchAgents easy.

## Usage

    lch	load <name>   - load an agent installed by lch
    lch	unload <name> - unload an agent installed by lch
    lch	start <name>  - start a loaded agent
    lch	stop <name>   - stop a loaded agent
    lch	brew <name>   - load an agent from an homebrew formula and tell it not to start at boot
    lch	unbrew <name> - unload agent from an homebrew formula
    lch	list          - list agents installed by lch
    lch	cat <name>    - show plist of agent
    lch	rm <name>     - remove an agent installed by lch
