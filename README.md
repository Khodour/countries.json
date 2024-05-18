# Country Data JSON

This repository contains a JSON file with data about countries around the world. Each country object in the JSON file includes the following attributes:

- **name**: The name of the country.
- **unicode**: Unicode representation of the country's flag.
- **emoji**: Emoji representation of the country's flag.
- **alpha2**: ISO 3166-1 alpha-2 code of the country.
- **dialCode**: International dialing code for the country.
- **alpha3**: ISO 3166-1 alpha-3 code of the country.
- **region**: The geographical region of the country.
- **capital**: The capital city of the country.
- **geo**: Geographic coordinates (latitude and longitude) of the country's capital.
- **timezones**: List of time zones associated with the country.

## Example Country Object

```json
{
    "name": "Afghanistan",
    "unicode": "U+1F1E6 U+1F1EB",
    "emoji": "\ud83c\udde6\ud83c\uddeb",
    "alpha2": "AF",
    "dialCode": "93",
    "alpha3": "AFG",
    "region": "Asia",
    "capital": "Kabul",
    "geo": {
        "lat": 33,
        "long": 33
    },
    "timezones": [
        "Asia/Kabul"
    ]
}
