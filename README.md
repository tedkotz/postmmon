# postmmon
Postfix Mail Box Monitor. This sends mail notifications when a user has too much mail.

Initially written by Eduardo Mendes and Ricardo Malafaia.
The original code can be downloaded here:
http://www.cpan.org/modules/by-authors/id/R/RM/RMALAFAIA/postmmon/postmmon_v.0.0.6

## Requirements
- perl
- postfix
- mbox format inboxes?

## Install
1. Update configuration
2. Place in /usr/local/sbin/
3. Add to cron
    1. link to cron.dauly
    2. or add to cron tab
4. Create /etc/postfix/mboxfull
5. Test run

## TODO
* [ ] Incorporate changes from offline version
* [ ] Add quiet/verbose mode
