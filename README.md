# Aago

A repo of date/time functions written in/for [Yorlang](https://github.com/anoniscoding/yorlang).

## Functions

Find the available functions below:

### muIseju(nomba)

Takes a number argument, between 0 and 59, representing minutes and returns its Yoruba equivalent as text.

### muWakati(nomba)

Takes a number argument, between 0 and 24, representing hours and returns its Yoruba equivalent as text.

### muWakatiAtiIseju(nomba, nomba)

Takes hours as its first argument and minutes as its second, returning the time as Yoruba text. E.g. `muWakatiAtiIseju(11, 45)` returns `"Aago Mejila Ku iseju Marundilogun"`.