# Lancet

A project inspired by the wonderful q - "Quick-and-dirty debugging output for tired programmers"

# Roadmap

## Desired API

Note, I've written no code. And from my brief search this type of reflection in javascript might not be possible.
We persevere.

```
var l = require('lancet');

var foo='bar';
l.l(foo);
```

This causes a temporary file to be created and/or appended at `$TMPDIR/l`.

```
[2012-11-04T14:51:06.157Z] line 3: foo='bar'
```