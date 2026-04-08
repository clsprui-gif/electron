# EnableHeapProfilingOptions Object

* `mode` string (optional) - Controls which processes heap profiling will be enabled
  for. Equivalent to `--memlog` in Chrome. Can be `all`, `all-renderers`, `browser`,
  `gpu`, `manual`, `minimal`, `renderer-sampling`, `utility-and-browser`, `utility-sampling`,
  or `all-utilities`. Default is `all`.
* `stackMode` string (optional) - Controls what kind of stack trace data is recorded.
  Equivalent to `--memlog-stack-mode` in Chrome. Can be `native`, `native-with-thread-names`.
  Default is `native`.
* `samplingRate` number (optional) - Controls the sampling rate. Equivalent to
  `--memlog-sampling-rate` in Chrome. Must be between `1000` and `10000000`. Default is `1000000`.
