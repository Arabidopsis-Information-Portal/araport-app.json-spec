# araport-app.json specification

### name

**Required**
Type: `String`

The name of the application.

- Must be unique per namespace.
- Should be slug style for simplicity, consistency and compatibility. Example: locus-viewer or blast-plus
- Lowercase, a-z, can contain digits, 0-9, can contain dash or dot but not start/end with them.
- Consecutive dashes or dots not allowed.

### description

*Recommended*
Type: `String`

A description of the application.

### html

**Required**
Type: `String`

The HTML file that contains the application's layout.

### scripts

**Required**
Type: `String`

The JavaScript file that contains the application's code.

### styles

Type: `String`

The CSS file that contains additional styles for the application.
