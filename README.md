# asterips

Asterisk brute force watcher
J. Oquendo
run from cron...

Some users may have to change their fields in awk depending on distro
and logging.conf settings... Easiest way to test this, is to run this
as a one liner and check the output before putting it in cron
tested on FC5 & Debian and it worked fine... I don't advise you run
this on a production machine until you've fully tested it against
your own logs and system.
