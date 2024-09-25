# QueueManager Plugin

Alpalis QueueManager is the ideal plugin for most servers. It allows you to manage the queue and the number of slots on the server. This helps you to enter your server without any problems.
<br>Plugin can be bought on https://imperialplugins.com/Unturned/Products/ALP-QueueManager.

## Features

- Option to set up any number of slots for players
- Possibility to set a different number of visible player slots from the actual ones
- Ability to set the number of slots separately for administrators and vips
- Ability to let any person pass in the queue by using the command
- Configurable whitelist with customised explanation

## Commands:

- /skipqueue - Bypass players in the queue.
- /slots - Display amount of slots.

## Config:

    QueueEnabled: true # If set to false, the queue will work as in normal Unturned
    ServerSlots: 24
    VisibleServerSlots: 24
    QueueSlots: 24
    CasualSlots: 24
    VIPSlots: 0
    AdminSlots: 0
    Bypassers: # List of SteamIds
    #  - 00000000000000000
    WhitelistEnabled: false
    Whitelist: # List of SteamIds
    #  - 00000000000000000   

## Permissions:

    Alpalis.ItemRestriction:adminticket - Administrator ticket for a slot on the server.
    Alpalis.ItemRestriction:vipticket - VIP ticket for a slot on the server.