---
name: Bug report
about: Create a report to help us improve
title: ''
labels: bug
assignees: ''

---

**Information**
<!-- If your issue is related to a Logitech device please make sure you are running at least Linux 5.2 -->
- `ratbagd` version (`ratbagd --version`):
- Piper version: 
- Distribution: 
- Device: 
- Kernel version (ex. `uname -srmo`): `KERNEL VERSION HERE`

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Please make sure your bug is reproducible with the CLI client, `ratbagctl`. If it is not open a bug report in libratbag instead.

Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Logs**
Please start the daemon with verbosity and reproduce the issue.

First make sure it isn't running already.
```
$ ratbagd --verbose=raw
OUTPUT HERE
```

**Additional context**
Add any other context about the problem here.
