# node-strict

Make your Node programs strict about stuff

This is a collection of "Node Commandments"

1. Thou shalt not call `process.exit`.  Let programs end gracefully.
2. Thou shalt behave properly in `"use strict"` mode, and respect its
   requirements.
3. Thou shalt not use synchronous I/O functions after startup.
4. Thou shalt not modify `require.extension` at run time, or rely on
   its modification by other modules.

## Usage

```javascript
require('node-strict')
```

That's it.  Now node is in super strict mode.
