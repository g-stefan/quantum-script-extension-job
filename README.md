# Quantum Script Extension Job

```javascript
Job(processMaxCount);
this.onStart(process);
this.onEnd(process);
this.onTimedout(process);
this.processMaxCount;
this.processMaxTicks;
this.clockTick;
this.setProcessMaxTime(miliSeconds);
this.setProcessMaxTimeSeconds(seconds);
this.setProcessMaxTimeMinutes(minutes);
this.addProcess(cmd,info,synchronizedKey);
this.addThread(fn,fnThis,parameters,info,synchronizedKey);
this.process();
```

## License

Copyright (c) Grigore Stefan

Licensed under the [MIT](LICENSE) license.
