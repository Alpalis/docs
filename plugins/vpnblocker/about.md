# VPNBlocker Plugin

Alpalis VPNBlocker is the ideal plugin for servers struggling with players bypassing IP bans. It includes implementations of 4 different APIs where each includes a free package.
Plugin can be bought on https://imperialplugins.com/Unturned/Products/VPNBlocker.

## Features

- 4 different APIs to choose from
- Mixed API which allows you to use all the APIs at once. This allows for an increase in the number of maximum queries from free packages
- Ability to set players who don't need to pass the VPN check
- Configurable message for a player that was rejected from the server

## Config:

```yaml
# Possible options: VPNAPI, PROXYCHECK, GETIPINTEL, IPHUB, MIXED
APIType: UNKNOWN
    
# VPNApi collects data and can detect with it's algorithm proxies, VPN, and Tor nodes
# It includes a free plan with hard limitation of 1000 queries per day
# To get API key, you have to register on their website https://vpnapi.io/
VPNApiKey: 
    
# Proxycheck is a premium proxy and VPN detection API
# It includes a free plan with hard limitation of 1000 queries per day
# To get API key, you have to register on their website https://proxycheck.io/
ProxyCheckApiKey: 
    
# IP Intelligence is VPN detection tool using advanced mathematical and modern computing techniques
# It's don't have coded limitations but author is asking to not exceed more than 500 queries per day & 15 queries per minute
# Custom packages are available, but you need to contact author
# Provided email address below must be valid else your service might be disabled without notice because there is no way to contact you
# For more informations check the official website of the project - http://getipintel.net/
GetIpIntelContactEmail: 
GetIpIntelPaidApiQuery:
    
# IPHub is an IP lookup website featuring VPN detection
# It includes a free plan with hard limitation of 1000 queries per day
# To get API key, you have to register on their website https://iphub.info/
IPHubApiKey:
    
PassOnBadRequest: false
    
IgnoredSteamIDs: # List of SteamIds
#  - 00000000000000000
```      