# 2.1.1
  - New dependency requirements for logstash-core for the 5.0 release
## 2.1.0
 - Implements `encode` with escaping according to the [CEF specification](https://protect724.hp.com/docs/DOC-1072).
 - Config option `sev` is deprecated, use `severity` instead.

## 2.0.0
 - Plugins were updated to follow the new shutdown semantic, this mainly allows Logstash to instruct input plugins to terminate gracefully, 
   instead of using Thread.raise on the plugins' threads. Ref: https://github.com/elastic/logstash/pull/3895
 - Dependency on logstash-core update to 2.0

