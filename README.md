# JavaScript String Formatter

A beginner-friendly JavaScript project that normalizes names before displaying them. It removes extra spaces, standardizes letter casing, and combines first and last names into a readable display name.

This project is based on the [String Formatter project](https://roadmap.sh/projects/js-string-formatter) from roadmap.sh.

## Features

- Removes whitespace from the beginning and end of names.
- Converts names to title case.
- Reuses small helper functions to format a complete display name.

## Functions

### `cleanText(text)`

Trims whitespace from the beginning and end of a string and converts the remaining text to lowercase.

### `capitalize(text)`

Uppercases the first character of a string while keeping the remaining characters unchanged.

### `formatDisplayName(firstName, lastName)`

Cleans and capitalizes both names, then returns them as a full display name.

## Usage

Run the JavaScript file with Node.js:

```bash
node stringFormat.js
```

Example:

```javascript
console.log(formatDisplayName('  ava', 'STONE  '));
console.log(formatDisplayName('nOAh', '  kim'));
console.log(formatDisplayName('  mINA  ', 'pATEL'));
```

Output:

```text
Ava Stone
Noah Kim
Mina Patel
```

## Requirements

- [Node.js](https://nodejs.org/) 12 or later

## License

This project is for learning purposes.
