# Valorant-observer-tool
**Status 13.03.2023: VALORANT features are currently not maintained. While we focus on League, we will not actively support Valorant Features of the toolkit.**

The observer tool is part of our [lol-prod-toolkit](https://github.com/RCVolus/league-prod-toolkit).
The tool is used to query local Valorant client APIs and send the data to a local or remote instance of prod-toolkit.
Once install, the observer tool automatically updates to any new versions released.

## Installation
1. Download the latest release [here](https://github.com/RCVolus/valorant-observer-tool/releases/latest)
2. Install and run the observer tool
3. Configure the toolkit instance:
* Open the settings file by selecting File -> Open Settings
* Configure the appropriate IP (`"server-ip": "127.0.0.1"` for locally hosted toolkit)
* Before saving, close the Observer Tool either from the tray or with File -> Quit
* Save the changed config file

## Usage
The power button at the bottom connects to the configured toolkit instance.
To connect to local VALORANT Client APIs, click Sync on the modules you need. The VALORANT Client needs to be running.

## Legal Disclaimer
league-prod-toolkit was created under Riot Games' "Legal Jibber Jabber" policy using assets owned by Riot Games. Riot Games does not endorse or sponsor this project.
