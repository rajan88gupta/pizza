---
name: Bug report
about: create a report to help us improve.
title: [ISSUE]
---

### Does your log mention database corruption?

If your Website log reports panics because of database corruption it is
most likely a fault with your system's storage or memory. Affected log
entries will contain lines starting with `panic: leveldb`. You will need to
delete the index database to clear this, by running `syncthing
-reset-database`.

### Include required information

Please be sure to include at least:

 - which version of Website and what operating system you are using
 - browser and version, if applicable
 - what happened,
 - what you expected to happen instead, and
 - any steps to reproduce the problem.
