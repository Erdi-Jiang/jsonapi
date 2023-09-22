# Description

---
* This is a library that extends from standard json library that supports encoding and decoding for complex and range.

# Installation

---
## Development Mode
* In the root directory, run the following: `pip -install -e`

# Examples

---
```angular2html
from jsonapi import jsonapi
range_serialized = jsonapi.dumps(range(1, 10, 2)
range_deserialized = jsonapi.loads(range_deserialized)
```
