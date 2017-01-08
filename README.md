# homebridge-yr

A homebridge temperature sensor for displaying the weather at your current location using data from yr.no.

# Installation

1. Install Homebridge using: `npm install -g homebridge`
2. Install this plugin using: `npm install -g homebridge-yr`
3. Update your Homebridge `config.json` using the sample below.

# Configuration

```json
{
  "accessory": "Yr",
  "location": "Norge/Oslo/Oslo/Oslo",
  "name": "Yr"
}
```

Fields:

* `accessory` must be "Yr" (required).
* `location` location query string (resembles to <a href="http://www.yr.no/sted/Norge/Oslo/Oslo/Oslo/varsel.xml">location</a>) (required).
* `name` is the name of the published accessory (required).

