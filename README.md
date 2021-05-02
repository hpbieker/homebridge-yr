# homebridge-yr

A homebridge temperature sensor for displaying the weather at your current location using data from yr.no.

# Installation

1. Install Homebridge using: `npm install -g --unsafe-perm homebridge`
2. Install this plugin using: `npm install -g --unsafe-perm homebridge-yr`
3. Update your Homebridge `config.json` using the sample below.

# Configuration

```json
{
  "accessory": "Yr",
  "location": "lat=57.68333&lon=11.93333&altitude=36",
  "name": "Yr"
}
```

Fields:

* `accessory` must be "Yr" (required).
* `location` location query string (resembles to <a href="https://api.met.no/weatherapi/locationforecast/2.0/compact?lat=57.68333&lon=11.93333&altitude=36">location</a>) (required).
* `name` is the name of the published accessory (required).

