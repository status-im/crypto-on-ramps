# Crypto On Ramps

A curated list of crypto-currency markets that facilitate the purchase of crypto for fiat currency.

## The list

[See the full JSON list here](https://raw.githubusercontent.com/status-im/crypto-on-ramps/master/ramps.json)

## On Ramp structure

JSON example:

```json
{
    "name": "Wyre",
    "description": "A secure bridge for fiat and crypto",
    "fees": "from 2.9%",
    "region": "US & Europe",
    "logoUrl":"https://www.sendwyre.com/favicon.ico",
    "siteUrl": "https://pay.sendwyre.com/purchase",
    "hostname": "sendwyre.com"
}
```

|Field Name|Type|Description|
|---|---|---|
|`name`|string|The name of the on-ramp service|
|`description`|string|A short line of text describing the on-ramp service|
|`fees`|string|The rate or rates that users are charged for the currency exchange service|
|`region`|string|The geo-political jurisdiction that the service operates in|
|`logoUrl`|string|A url to the on-ramp service's logo|
|`siteUrl`|string|A url to redirect a user to the on-ramp service's exchange service|
|`hostname`|string|The hostname of the `siteUrl` consisting of the domain name and tld|