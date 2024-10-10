Test 

All configuration is done inside the application, no extra config is required in files. </br>
At first boot you will be redirected to the settings page.

## General

These settings are OK for most installations.

| Param        | Description           |
| ------------- |:-------------:|
| Hostname      | The hostname or IP of the host Maintainerr runs on |
| Api key       | Maintainerr's API key. Which has no use yet. |

## Plex

This is the only **required** configuration. Without a valid Plex connection Maintainerr won't be able to function.

When using a local Plex instance, make sure your Plex's 'secure connections' network setting is set to 'preferred' instead of 'required'.
If you'd like Maintainerr to communicate securely, you'll have to use your '*.plex.direct' URL as the hostname. You can copy this URL from Overseerr's configuration. Make sure you include 'https://'.

| Param        | Description           |
| ------------- |:-------------:|
| Name          | The name of your server |
| Hostname or IP| The domain name or local IP of the host your server runs on |
| Port          | The port Plex runs on, default is 32400 |
| Authentication| Authenticate with your Plex server using a **admin** account |

## Overseerr

Overseerr's configuration is required to use it's parameters in rules and to remove requests. </br>

| Param | Description |
| ------------- |:-------------:|
| Hostname or IP| The domain name or local IP of the host your server runs on |
| Port          | The port Overseerr runs on |
| Api key  | Overseerr API key, should be visible in the Overseerr settings |

## Radarr

Radarr's configuration is required to use it's parameters in rules and to remove or unmonitor movies.

| Param | Description           |
| ------------- |:-------------:|
| Hostname or IP| The domain name or local IP of the host your server runs on |
| Port          | The port Radarr runs on |
| Api key   | Radarr API key, should be visible in the Radarr settings |

## Sonarr

Sonarr's configuration is required to use it's parameters in rules and to remove or unmonitor shows.

| Param | Description           |
| ------------- |:-------------:|
| Hostname or IP| The domain name or local IP of the host your server runs on |
| Port          | The port Sonarr runs on |
| Api key   | Sonarr API key, should be visible in the Sonarr settings |

## Tautulli (currently only available in the dev branch)

Tautulli's configuration is required to use it's parameters in rules.

| Param | Description |
| ------------- |:-------------:|
| Hostname or IP| The domain name or local IP of the host your server runs on |
| Port          | The port Tautulli runs on |
| Api key  | Tautulli API key, should be visible in the Tautulli settings |

:material-clock-edit: Last Updated: 10/10/24