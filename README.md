# Attendance schedule

Public clock for the private attendance repo. GitHub does not run scheduled
workflows on a private repository for this account, so this repo starts
[nova-hr-attendance-cron](https://github.com/mohamed-kharashy/nova-hr-attendance-cron)
at 09:25 and 17:25 Cairo time, Sunday to Thursday. That repo then waits and
punches at 10:00 and 18:00.

No passwords are stored here. `DISPATCH_TOKEN` is an Actions secret.
