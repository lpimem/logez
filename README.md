# logez

Minimal console logger.

Sample usage: 

```Typescript
import { debug, info, warn, error, LogLevel, setLogLevel} from 'logez';

let name = "world";
debug(Date());
info("Hello", name);
warn("something is not feeling right");
error("something is dead wrong");

// ....

setLogLevel(LogLevel.INFO);
```