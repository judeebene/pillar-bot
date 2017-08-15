# Mattermost Bot 

## Overview

The Bot  use the Mattermost [Go driver](https://github.com/mattermost/platform/blob/master/model/client.go) to interact with a Mattermost [hosted server](https://community.pillarproject.io), listen to events and respond to messages. Documentation for the Go driver can be found [here](https://godoc.org/github.com/mattermost/platform/model#Client).

Highlights of APIs used in this sample:
 - Log in to the Mattermost server
 - Create a channel
 - Modify user attributes 
 - Connect and listen to WebSocket events for real-time responses to messages
 - Post a message to a channel

## Using getting started code from [sample-go-bot](https://github.com/mattermost/mattermost-bot-sample-golang.git)

1 - [Install](http://docs.mattermost.com/install/requirements.html) or [upgrade](https://docs.mattermost.com/administration/upgrade.html) to Mattermost server version 3.10+, and verify that the Mattermost server is running on [http://localhost:8065](http://localhost:8065). 

