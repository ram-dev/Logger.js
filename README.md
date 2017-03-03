# Logger.js is wapper class using Winston logger

## Overview

This Logger will create separate log for the debug-log file and other will be save on all-logs file

Install dependencies:
```sh
npm install winston
```

## Example


```sh
logger = require( 'Logger.js' );
logger.debug( 'your debug statement' );
logger.warn( 'your warning' );

```
