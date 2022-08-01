---
# BEGIN FILE CONFIGURATION YML HEADER >>>>>
# autoconfig.yml will use these settings. config.yml will override.
Type: Lesson
UID: a1536779-8dd7-4d0e-bf02-7420bbd549ce
# DefaultVisibility: hidden # Uncomment this line to default Lesson to hidden
# END FILE CONFIGURATION YML HEADER <<<<<
---

# Common Scrum practices

> Estimated Reading Time:


## Product backlog

The Product Backlog is an ordered list that contains all of the user stories, or grouped together stories often called Epics, that are needed in the product. It is a prioritized list of these user stories that is maintained by the Product Owner. This list of items helps the Product Owner and development team track what is believed to be the most important thing to build next.

The list is prioritized according to the value that will be delivered to the customer. Items on the list should contain: a description, an estimate, and the value it would provide. `User Stories` are a common item that will appear on a backlog (some would argue the only thing that should appear). They define the who the feature is for, what it is, and why the user wants it. `User Stories` are typically written by the Product Owner and should *NOT* contain information about _how_ a story is to be implemented. This ties into the value of *self-organized* teams.

A typical template for a user story looks like the following:

```text
As (user name)
I want (description of feature)
So that (reason for feature).
```

The Product Backlog should be continuously updated. As new information is revealed during the development effort the feedback from Sprint Review meetings, customers, stakeholders, and developers will cause some items on the backlog to become out of date. Other new items may also be revealed as these conversations happen and new opportunities are discovered.

### !callout-info
For a quick video introduction to the Product Backlog refer to this video: [Scrum Alliance - Product Backlog](https://youtu.be/vbKcZiA_4iM)
### !end-callout

## Sprint planning meeting

Sprint planning meetings happen at the beginning of every sprint and are attended by the Scrum Master, Product Owner, and the Development Team. This purpose of the meeting is to determine which user stories will be accepted in to the next sprint of 1-4 weeks.

To begin the Scrum Master or the facilitator of the meeting should review any action items that arose during the previous sprint retrospective. Then the Product Owner should describe any new product or marketing updates. After these updates have been reviewed it is time for the more complex part of the meeting which is the planning conversation.

During the planning conversation the sprint goal should set the vision for what value the development team should hope to achieve. Understanding what type of value the team can deliver to the customer helps the team look for all of the relevant stories in the backlog that could maximize that value. If the Product Backlog is maintained regularly and prioritized correctly, the team will primarily focus on how many of the highest priority items they believe they can accomplish within the sprint. This negates any need for the team to discuss items that would be further down in the backlog and prevents spending extra time on non-valuable discussions.

Each backlog item is assigned a *story point* value. Story points are a number (typically between 1-13 using the Fibonacci sequence) assigned to a given backlog item that is an attempt to estimate the amount of work (effort/difficulty) the Development Team believes the item will take to complete. This numbering sequence is a _fuzzy guess_ that the team attempts to assign based on previous work done, however many businesses have tried to equate the value to a time estimate. This is not advisable since time estimates are likely put a pressure on the team to inflate the story point value assigned to each story and thus incorrectly answers the question of how hard the item is.

In order to determine what a reasonable number of backlog items are that the team feels they could tackle within a sprint, the team may review their `velocity`. The Velocity of the team is calculated as a simple average of the story points the team has completed over the past several Sprints. Then, based on this velocity and their estimated story points for the upcoming backlog items, they will select as many of those items they determine can be reasonably accomplished within the Sprint. Several other factors must be considered such as vacations, dependencies, access to tooling, and available skills of the team. This could adjust the teams estimates for any given Sprint.

Velocity is one of the most highly contentious concepts in Agile and Scrum, but offer an important metric for helping the team make the determination of which items they believe they can reasonably do. One of the more common abuses of velocity is to compare the various velocities among different teams to try and determine which teams are more efficient. Although this may sound practical, according to [Goodhart's Law](https://en.wikipedia.org/wiki/Goodhart%27s_law), this then destroys the utility of velocity. Teams will then be pressured into inflating their story point values to make it appear as if they are accomplishing more work. Such pressures should be carefully avoided.

After the backlog items have been selected for the Sprint, a recap of the plan is done. In this phase of the meeting action items are reviewed and assignments of the work are also reviewed. This way everyone is aware of the next steps they are each to take to being the Sprint.

### !callout-info
For a quick video introduction to the Sprint Planning meeting refer to this video: [Atlassian - Sprint Planning Meetings](https://youtu.be/9NWbQlRcdh0)
### !end-callout

## Release planning meeting

Release planning meetings are where the development team tries to determine which items they can commit to that would constitute a suitable set of features that should be released together. Releases span several sprints and may happen in regular intervals, or varying intervals depending on client needs. Below is a graphical representation of releases, sprints, and feature work:

![Releases, Sprints, and Features](../assets/Releases-Sprints-Features.png)

The work of a Release Planning meeting is to identify how many of the features can be done within the release cycle, and which features would likely be completed within each sprint. Below is a graphical representation of this.

![Release Planning](../assets/ReleasePlanning.png)

The Release Planning meeting also give the team an opportunity to communicate with one another on the expectations and vision of the product.

In order to conduct the release planning meeting, a product backlog must exist which contains a prioritized set of items the product requires. The Product Owner should have the items ordered by priority, however during the Release Planning meeting the Development Team may requires that the order of these items be changed to accommodate for things such as absences, technical requirements, external dependencies, or research. There must also be a shared understanding of the product vision and understanding of the consumers who will be using the product to help determine which items should be prioritized. This also helps the team stay motivated to continue working on the product.

To begin the Release Planning meeting, the Scrum Master or facilitator should begin by reviewing the vision and the roadmap for the product. Next the team should review the technical requirements and architecture of the product. After some review of the roadmap, vision, and technical requirements the team should try to determine a theme of the next release to help identify items and features that can be grouped together. This is also typically accompanied by a name for the release to help objectify it's contents.

Next the team should review their velocity to help set a proper expectation of how much work can be completed before the end of the release cycle. They should also review and update their *Definition of Done* to solidify everyone's understanding of how much work must actually be done to complete each backlog item aside from just the coding.

After all of the review items are complete, the Product Owner can now present the backlog items in their prioritized order according to their discussions with the customer. The team then goes about the work of creating high-level estimates of the amount of work the team believes is required to complete the features. Any stories that are too large to fit into a single sprint should be broken down into two or more smaller stories. Stories should not be broken down by technology but rather separate pieces of functionality delivered to the user.

### !callout-info
For a quick video introduction to the Release Planning meeting refer to this video: [Rally - Release Planning](https://youtu.be/gYX19iIzECQ)
### !end-callout

## Daily Scrum meeting

The Daily Scrum meeting (sometimes called the Daily Stand-up) should take fewer than 15 minutes to complete. Any discussion that require depth should be shelved into a separate meeting often called the *Parking Lot* which happens immediately after the Daily Scrum. This allows everyone to leave after the daily scrum meeting who does not wish to participate in the *Parking Lot* meeting.

The purpose of the Daily Scrum meeting is to communicate the progress of the backlog items that each team member is responsible for. This typically takes on the form of one of two formats. One of the most often used formats is a round-robin style call out of the work the individual did the day before, the current day, and any blockers they have. Another common format is called _walking the board_. This is where the items listed in the columns of a project board are reviewed one by one and any participants working on the item are allowed to give an update.

By having the Daily Scrum meeting, it is hoped that there will be fewer long format meetings necessary to synchronize work among the team members. It is important to keep the Daily Scrum meeting short, therefore only the Development Team members should be active participants of the meeting. The Scrum Master and Product Owner should act only as observers of the meeting so that they themselves know the status of the work. Scrum Masters and Product Owners are allowed to participate in the Parking Lot meeting which happens afterwards where more depth of discussion can take place.

### !callout-info
For a quick video introduction to the Daily Scrum meeting refer to this video: [Atlassian - Daily Standups: How to Run Them](https://youtu.be/er9gntPjTJU)
### !end-callout
