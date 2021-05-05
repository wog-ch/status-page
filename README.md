# WoG Status Page

## Installation

To start clone this repository and run `npm install`.


## Create Incidents

To create an incident run `npm run new-incident`.

## Update Incidents

To update an incident (e.g. to set it to resolved) run `npm run update-incident`

## Delete Incidents

To delete an incident run `npm run delete-incident`. Be aware this deletes the
incident completely with all available translations and will not be visible in
the history anymore.

## Deploy

Deployment has to be done after each incident creation. To deploy the changes,
generate the pages with `npm run generate` and afterwards run `npm run deploy`
to deploy it to [https://status.wog.ch](https://status.wog.ch).

This needs a few seconds/minutes until the page gets updates.
