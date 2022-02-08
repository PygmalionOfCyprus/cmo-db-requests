We are excited to introduce a new system for DB requests!

Instead of using the old "DB Request Thread," we'd like to encourage everyone to post their DB requests in our new public issue tracker on GitHub.

GitHub offers numerous improvements over the legacy system, both for reporters and for the DB team. However, changing long-running systems can be disruptive, even controversial. We'd therefore like to go into a little more detail about why we opted to make this shift.

## What Was Wrong with the Old System?
Under the old system, users posted their DB requests in one of the "DB Request Threads." Without guidance, these ranged from carefully researched multi-page reports to random Twitter links.

At (ir)regular intervals, we would have to manually copy these posts into our internal tracker (MantisDB). This ate up large chunks of time. 

Due to the high volume of requests, we were generally unable to effectively sort or triage issues we were pulling from the request threads. It became extremely difficult to distinguish between bugs that warranted immediate attention, well-researched requests we wanted to act on, and chaff. 

Unsorted and unprioritized, issues quickly overwhelmed the team, who felt as if they were "drinking from a fire hose." At the time of our internal transition, there were over 2,500 "open" issues clamoring for attention in Mantis. Some were nearly a decade old. We estimated that less than 1/3 of these issues were actionable: the rest did not have enough information, were duplicates of other issues, had been handled in a previous DB version, etc. The DB team was spending more time picking through issues than actually handling them!

Moreover, because issues were being tracked off-site on a platform inaccessible to the original reporters, it was effectively impossible for us to follow up. This was frustrating to both sides. We had no way of asking questions or requesting additional research, and reporters had no way of knowing the status of their requests.

## Why Move to GitHub?
The previous paradigm was unsustainable. Staying the course was not an option.

We considered several forum-based solutions, including expanding the extant request threads into a subforum, or even creating an externally-hosted site which we could configure to our liking. However, we determined that those options would not address our biggest problems with the legacy system.

GitHub offered an alternative with numerous advantages:

* It was a platform we were already using internally
* We could create "issue forms" and templates to guide submissions
* We could use labels and milestones to categorize and prioritize work
* We could coordinate workload across both our private dev tracker and the public tracker without requiring manual copy-over
* Requests were "threaded," letting us communicate directly with reporters per-issue
* People could easily track the status of their submitted issues (or any issue they were interested in)
* Community members could support development beyond just submitting their own issues, e.g., by providing research for incomplete requests

GitHub's roots in version control and open-source development also offered some tantalizing possibilities for community collaboration. For example, the ongoing [Review and Editing of Unit Descriptions]() could be handled as a branch on this (or a separate) repository, allowing users to make additions and edits before submitting a pull request for review by the project managers. 

But that's getting ahead of things.

Having identified GitHub as the most promising option, we proceeded to transition our internal tracker from MantisDB to a private, issue-only GitHub repo similar to what the public tracker would become. This offered an opportunity for us to adjust our workflow for GitHub Issues, to establish systems (e.g., labels) for the new tool, and to confirm that GitHub was the right choice for our needs. Every member of the team agreed that the trial was a resounding success, and we made the final decision to transition DB reporting fully to GitHub.

## How Does It Work?
At first glance, GitHub can be intimidating to new users. However, it is very easy to use.

First, we recommend you read the README on the repo "homepage" (found under "Code").

Next, navigate over to the "Discussions" tab. The "Discussions" tab is essentially a mini-forum, intended as a place to discuss DB requests and research or to ask questions / make suggestions about the GitHub repo itself. We've made a couple starting posts you may find helpful, including a list of (anticipated) FAQs.

Finally, when you're ready to make your first DB request ("opening an issue," in GitHub parlance), just navigate over to the "Issues" tab. There, you'll see a list of open issues, and be able to submit new issues yourself. We've set up a number of "issue forms" to guide users; we *highly* encourage using these forms where possible, but if absolutely necessary, you can still create a freeform request. For now.

## In Conclusion
Any major change must be preceded by carefully considering the advantages (and disadvantages) of either moving forward or staying the course. Having outlined our reasoning above, we hope you can see why we've opted to push ahead -- and that you all will enjoy taking advantage of the many benefits of GitHub Issues as we have!

This is still an early-stage process; inevitably, there will be growing pains. Please bear with us when there are.