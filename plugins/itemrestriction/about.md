# ItemRestriction Plugin

Alpalis ItemRestriction is the ideal plugin for any server. The plugin provides extensive item restriction options and easy-to-use configuration.
<br>Plugin can be bought on https://imperialplugins.com/Unturned/Products/ALP-ItemRestriction.

## Features:


\- Ability to restrict all items at once by setting whitelist to true and changing default whitelist item settings.<br>
\= Ability to restrict an item during an event, e.g. when crafting it.

## Config:

    InvertPickingUpBlackList: false
    PickingUpBlackList:
    #  - Id: [item id]
    #    Permissions: # List of permissions
    #      - "firstpermission"
    #      - "secondpermission"
    
    InvertHoldingBlackList: false
    HoldingBlackList:
    #  - Id: [item id]
    #    Permissions: # List of permissions
    #      - "firstpermission"
    #      - "secondpermission"
    
    InvertEquippingBlackList: false
    EquippingBlackList:
    #  - Id: [item id]
    #    Permissions: # List of permissions
    #      - "firstpermission"
    #      - "secondpermission"
    
    InvertUnEquippingBlackList: false
    UnEquippingBlackList:
    #  - Id: [item id]
    #    Permissions: # List of permissions
    #      - "firstpermission"
    #      - "secondpermission"
    
    InvertCraftingBlackList: false
    CraftingBlackList:
    #  - Id: [item id]
    #    AllBlueprints: false
    #    Blueprints: # List of blueprint indexes
    #      - 1
    #    Permissions:
    #      - "firstpermission"
    #      - "secondpermission"

## Permissions:

    Alpalis.ItemRestriction:bypass - Allows you to bypass all restrictions.