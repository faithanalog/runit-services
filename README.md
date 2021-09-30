# runit-services

personal service scripts for use with [runit](http://smarden.org/runit/index.html)

oneshot services in this repo use [permafrost](https://github.com/faithanalog/permafrost).

scripts are tuned to log to stderr; runit exposes these logs in `runsvdir` process name. watch logs in real time with `watch pgrep -a runsvdir`. for persistent logs, change scripts to log to stdout and add a log service (see [runit faq](http://smarden.org/runit/faq.html#createlog)).

