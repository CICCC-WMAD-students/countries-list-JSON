# The challenge
Your challenge is to build out a country listing using a local data.json to retrieve the data.

Your users should be able to:
- See all countries on the homepage
- Search for country using an input field
- Filter countries by region
- Click on a country to see more detailed information on a separate page
- View the optimal layout for each page depending on their device's screen size (Mobile - 375px, Desktop - 1440px)
- Toggle the color scheme between light and dark mode

# Data example
```json
[
  ...,
  {
    "name": "Canada",
    "topLevelDomain": [".ca"],
    "alpha2Code": "CA",
    "alpha3Code": "CAN",
    "callingCodes": ["1"],
    "capital": "Ottawa",
    "altSpellings": ["CA"],
    "subregion": "Northern America",
    "region": "Americas",
    "population": 38005238,
    "latlng": [60.0, -95.0],
    "demonym": "Canadian",
    "area": 9984670.0,
    "gini": 33.3,
    "timezones": [
      "UTC-08:00",
      "UTC-07:00",
      "UTC-06:00",
      "UTC-05:00",
      "UTC-04:00",
      "UTC-03:30"
    ],
    "borders": ["USA"],
    "nativeName": "Canada",
    "numericCode": "124",
    "flags": {
      "svg": "https://flagcdn.com/ca.svg",
      "png": "https://flagcdn.com/w320/ca.png"
    },
    "currencies": [{ "code": "CAD", "name": "Canadian dollar", "symbol": "$" }],
    "languages": [
      {
        "iso639_1": "en",
        "iso639_2": "eng",
        "name": "English",
        "nativeName": "English"
      },
      {
        "iso639_1": "fr",
        "iso639_2": "fra",
        "name": "French",
        "nativeName": "français"
      }
    ],
    "translations": {
      "br": "Canadá",
      "pt": "Canadá",
      "nl": "Canada",
      "hr": "Kanada",
      "fa": "کانادا",
      "de": "Kanada",
      "es": "Canadá",
      "fr": "Canada",
      "ja": "カナダ",
      "it": "Canada",
      "hu": "Kanada"
    },
    "flag": "https://flagcdn.com/ca.svg",
    "regionalBlocs": [
      {
        "acronym": "NAFTA",
        "name": "North American Free Trade Agreement",
        "otherNames": [
          "Tratado de Libre Comercio de América del Norte",
          "Accord de Libre-échange Nord-Américain"
        ]
      }
    ],
    "cioc": "CAN",
    "independent": true
  },
  ...
]
```