# timestamp_api
My implementation of the Timestamp API project from freeCodeCamp:

Implements the following User stories:
* I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016).
* If it does, it returns both the Unix timestamp and the natural language form of that date.
* If it does not contain a date or Unix timestamp, it returns null for those properties.

## Example usage:
`https://radiant-taiga-53469.herokuapp.com/March 7, 2016`
`https://radiant-taiga-53469.herokuapp.com/1457308800`

## Example output:
`{ "unix": "1457308800", "natural": "March 7, 2016" }`
