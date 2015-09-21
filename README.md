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
Type: `Array` of `String`

The JavaScript files that contain the application's code.

### styles

*Recommended*
Type: `Array` of `String`

The CSS files that contain additional styles for the application.
