CHANGELOG
=========

1.5 - XXX

XXX

1.4 - 2017-09-26
----------------

- statsd: moved from aiostatsd to aiomeasures
- Added --sizing and --sizing-tolerance (#72)
- Refactored shared counters
- Implemented a shared console (#42)
- Improved shutdown process (#67)
- Refactored fmwk.py (#25)
- Add a way to record requests and responses (#80)
- added --use-extension
- added events
- published tests/examples*.py to the docs (#90)


1.3 - 2017-07-28
----------------

- fixed file-based requests with sessions -vvv option (#73)
- proper managment of the verbose option in moloslave
- added uvloop support (#68)
- added initial PyPy support (#47)
- Added name & @scenario_picker() options (#65)


1.2 - 2017-06-15
----------------

- improved docs
- added delay options (#48)
- added --ramp-up option (#61)
- fix a bug on response display (#62)


1.1 - 2017-06-09
----------------

- added request and json_request helpers (#50)
- added session setup and teardown fixtures (#52)
- added set_var & get_var helpers (#54)
- fixed thhe code generated by molostart (#55)


1.0 - 2017-03-23
----------------

- Initial stable release
