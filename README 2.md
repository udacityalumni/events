--> Add an Event <--
===========

Submit an event using [this form](https://udacitycareers.typeform.com/to/S29jIh), or submit a pull request on Github. 


To add an event via Github:

Send a pull-request which adds a file to the `_conferences/` directory
with a new file representing the conference. The file should be named
with the event name and with an `.md` extension (for
example, `my-udacious-event.md`).

The contents of the file should use the following template:
```
---
name: "Droidcon"
website: http://uk.droidcon.com/2018/
location: London, UK
tags: Web (or Mobile, AI, Autonomous, Data, Business)

date_start: 2018-10-29
date_end:   2018-10-30

cfp_start: 2018-06-16  # Optional
cfp_end:   2018-07-21  # Optional
cfp_site: http://uk.droidcon.com/2015/lineup-2015/ # Optional, will default to website
---
```

*Note: Do not include the location of the conference in the name. The above conference is often referred to as "Droidcon London", but we will always render the location with the name so it is redundant.*


License
-------

All content is [CC0][1]. This template generously modeled off of the Android Conferences Github page. 

 [1]: https://creativecommons.org/publicdomain/zero/1.0/
