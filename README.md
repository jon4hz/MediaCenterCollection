# MediaCenterCollection
A collection of docker-compose files for a full stack Plex media center.

## Content
There are compose-files for the following services:
* Plex
* SABnzbd
* Sonarr
* Radarr
* Lidarr
* NZBHydra2
* Ombi
* Overseerr
* Tautulli
* Tdarr

## Prerequisites
The following tools are required for this setup.
* `docker`
* `docker-compose`

## Customization
Before starting the container, you should check all ports and paths in the individual compose files and adjust them if necessary.

## Start a service
To start a service, change to the corresponding folder with `cd` and execute `docker-compose up -d`.  
In order to have all the necessary networks available, you should start SABnzbd and Plex first.