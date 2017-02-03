# json-date-parser
Minimal function suitable for passing to JSON.parse to revive common date-time strings into Date objects

Implementation is cribbed straight from:

https://github.com/RickStrahl/json.date-extensions

Differences:
* This library does not add to the `JSON` object. It defines a completely separate function.
* TypeScript type information is included.
