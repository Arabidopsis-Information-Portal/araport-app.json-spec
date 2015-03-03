# araport-app.json specification

### namespace

**Required**
Type: `String`

The namespace within which the application is registered. Must be unique within
the Araport platform

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
Type: `Array` of `String`

A List of HTML files that contains the application's layout.

### scripts

**Required**
Type: `Array` of `String`

The JavaScript files that contain the application's code.

### styles

*Recommended*
Type: `Array` of `String`

The CSS files that contain additional styles for the application.
