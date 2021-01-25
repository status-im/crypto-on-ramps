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
    "logo-url":"https://www.sendwyre.com/favicon.ico",
    "site-url": "https://pay.sendwyre.com/purchase"
}
```

|Field Name|Type|Description|
|---|---|---|
|`name`|string|The name of the on-ramp service|
|`description`|string|A short line of text describing the on-ramp service|
|`fees`|string|The rate or rates that users are charged for the currency exchange service|
|`region`|string|The geo-political jurisdiction that the service operates in|
|`logo-url`|string|A url to the on-ramp service's logo|
|`site-url`|string|A url to redirect a user to the on-ramp service's exchange service|