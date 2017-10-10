# [atm-state-levels](https://www.npmjs.com/package/atm-state-levels)

A helper service to work with ATM state logical levels, used by [Electron ATM](https://github.com/timgabets/electron-atm) and [ATM State Navigator](https://github.com/timgabets/states-navigator) applications. 

## To Use:

```
>var LevelsService = require('atm-state-levels');
>var l = new LevelsService();
>l.getLevelSize(17)
0
> l.addState('903', 17)
true
> l.getLevelSize(17)
1
```
