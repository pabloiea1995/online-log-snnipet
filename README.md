
# online-log-snnipet 

This extensions includes a series of snnipets for the npm module online-log, to make it easier to write log code lines.

## Tutorial

To use the snnipts its important to configure npm online-log module main funciton as `log()` as shown below:

```javascript
//requiring and initializing online-log
const  online_log  =  require("online-log");

//asign logging main function
const  log  =  online_log.log;
```

The snnipets generate code for default log levels:
| Prefix |Result |
|---------------|---------------------|
| `logd` &rarr; | `log('DEBUG', '');` |
| `logt` &rarr; | `log('TRACE', '');` |
| `logi` &rarr; | `log('INFO', '');` |
| `logw` &rarr; | `log('WARN', '');` |
| `loge` &rarr; | `log('ERROR', '');` |
| `logf` &rarr; | `log('FATAL', '');` |
