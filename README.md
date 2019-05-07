# unRAID Docker Templates

These are my Docker container templates used to add Docker containers that are not on the Community Applicatins plugin.

## How to install a template
In order to use one of these containers, simply add the template file to `/boot/config/plugins/dockerMan/templates-user`.

Then, on the Docker tab in the unRAID web GUI, click `Add Container`. In the template dropdown, select the template you just added.

Fill the config as usual.

## Deprecations
* Traefik is now available on CA, so there are no reasons to use this template anymore.
