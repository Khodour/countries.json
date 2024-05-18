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
        "name": "United States",
        "unicode": "U+1F1FA U+1F1F8",
        "emoji": "🇺🇸",
        "alpha2": "US",
        "dialCode": "1",
        "alpha3": "USA",
        "region": "Americas",
        "capital": "Washington D.C.",
        "geo": {
            "lat": 38,
            "long": 38
        },
        "timezones": [
            "America/New_York",
            "America/Detroit",
            "America/Kentucky/Louisville",
            "America/Kentucky/Monticello",
            "America/Indiana/Indianapolis",
            "America/Indiana/Vincennes",
            "America/Indiana/Winamac",
            "America/Indiana/Marengo",
            "America/Indiana/Petersburg",
            "America/Indiana/Vevay",
            "America/Chicago",
            "America/Indiana/Tell_City",
            "America/Indiana/Knox",
            "America/Menominee",
            "America/North_Dakota/Center",
            "America/North_Dakota/New_Salem",
            "America/North_Dakota/Beulah",
            "America/Denver",
            "America/Boise",
            "America/Phoenix",
            "America/Los_Angeles",
            "America/Anchorage",
            "America/Juneau",
            "America/Sitka",
            "America/Metlakatla",
            "America/Yakutat",
            "America/Nome",
            "America/Adak",
            "Pacific/Honolulu"
        ]
    }
