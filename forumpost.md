## Why Migrate?
When transitioning away from a long-used system, one must weigh the disruption of change against the advantages one stands to gain. This is doubly true in the wargaming community: grognards generally like things to stay as they are, thank you very much!

However, we feel strongly that the current "DB Requests" system is no longer sustainable.

Under the old system, users with requests or recommendations would create freeform posts in one of the aforementioned forum threads. There was no guidance, so posts ranged from carefully researched multi-page reports to Twitter links dropped without context. Nor were requests "threaded": responses to previous posts appeared in the same "feed" as new requests. This Matryoshka-esque chaost

The current state of the old threads can be summed up with a word: *bloat*. 

Nearly a decade of posting and community growth has left the old threads spanning hundreds of pages.

Fed in part from the DB threads, this bloat spread to our legacy issue tracking systems and metastasized. Today, our legacy tracker groans beneath the weight of over 2,500 "open" issues, some nearly ten years old. Few tickets have been triaged, tagged, or even categorized. Duplicates abound. Many issues were handled but never closed: we found DB team members were increasingly picking up ostensibly open tickets only to discover the work was done years ago.

It became clear that the legacy tracker had become an obstacle rather than a help. Last month, 

* Issues and requests must be manually copied into our internal issue tracker
* Once copied, the original submitter has no way of tracking progress or knowing when/if an issue will be handled
* Database workers cannot easily request more information from the original reporter as part of their workflow
* No search functionality
* No labelling/tagging, milestones, or other basic sort features
* With no forms or guidelines, requests vary wildly in usefulness; many are entirely unactionable and serve as little more than chaff

Some of these issues can be mitigated with varyingly complex solutions. For example, opening a "DB Requests Subforum" modelled after the Tech Support Forums would allow for threaded issue reporting and a functional -- if clunky -- way of letting original submitters. Piecemeal fixes 