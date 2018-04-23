# Dev Team Standup at Artsy

We've been doing engineering standups for as long as there has been an engineering team. The formats have changed over
time as the size and scope of Artsy has changed. We're now on our fourth iteration of this process.

A standup is ideally ran by two people, one person talking, the other taking notes. Decide amongst yourselves which of
you will do the before standup stuff.

**Note**: We document our standup process to the degree that _anyone_ on our team can run the standup because we believe
that _everyone_ should run at least one meeting. These standups are important for team cohesion and cross-team knowledge
sharing; they are an organization-wide responsibility and every engineer should participate.

### Ten minutes before a standup

* The person handling the talking parts `@here`s the dev channel. Include where the meeting is in the NYC office
  (usually the Classroom).
* The same person reminds last week's on-call staff in #dev to prepare their updates about last week's rotation. Something like:
  > @personA @personB reminder, we're looking for a list of major or notable incidents from last week during standup.
* The same person reminds the team leads in #dev to prepare their tweet-sized updates, something like this:
  > friendly reminder: we’re doing summary updates from tech leads during open standup, so have yours ready! 
  > /cc @tech-leads

### What is a good update?

* Should focus on status of product work
* Raises larger technical changes which affect other teams
* Talks about the team effort rather than an individual's work

### During standup

* We start off with props, as a nod towards [People are Paramount][pplp]
* Then we get an update from the CTO
* Then an update from the Product team
* Then an update from the current on-call support team
* Each tech lead gives a summary of what their teams have been up to
* We leave a spot for potential cross-team issues
* We have a spot to talk about things people are proud of
* We then either announce [the Lunch & Learn][ll], or try find one for the week

During the standup, someone writes up these notes and passes them out on to Slack after. Everyone leaves links to things
they have commented on during the meeting, if they don't, we chase them up.

## Our Markdown Template

```md
_Props_

-

_CTO Update_

-

_Product Team Updates_

-

_On-call Support Updates_

-

_Team Updates_

* Grow:
* Discover:
* Evaluate:
* Purchase:
* Sell:
* Platform:

_Cross-dependencies / Requests for Pairing_

-

_New Milestones / Repos / Blog posts_

-

_Lunch & Learn_

-

_Closing Announcements_

* Ash will be available on Wednesday from 2–3 on the 24th floor, or over Slack, to assist with writing projects. If
  you're writing a blog post, proposing a conference talk, or writing documentation, this is where you can come for
  help.
* Show & Tell is this Friday at 11:30 NYC time in the Studio on 24 (and over Zoom). See the docs for more info:
  https://github.com/artsy/meta/blob/master/meta/show_and_tell.md
* We're looking for volunteers to run next week's standup! We need two volunteers: one person to take notes and one
  person to do the talking.
  * Okay great! We've got [INSERT VOLUNTEERS NAMES HERE] running this next week.
*
```

[pplp]: https://github.com/artsy/meta/blob/master/meta/what_is_artsy.md#people-are-paramount
[ll]: https://github.com/artsy/meta/blob/master/meta/lunch_and_learn.md
