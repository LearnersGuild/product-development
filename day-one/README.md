# Your First Day

Congratulations on becoming a member of the LOS development team! This part of the guide is meant to get you oriented, and with any luck, up-and-running on all of our software services on your local development machine.

## Getting Started

Please keep in mind that, from time to time, this guide may become outdated. If you notice that it _has_ become outdated, please check out this repository, fix it, and submit a pull request. You'll be saving every person after you time if you do this. **Be a hero.**

### 1. Read This Guide in Its Entirety

Okay, that may not be very satisfying, as it doesn't get you any closer to having things running, but it's pretty crucial. We're a distributed team, which means that we rely heavily on written documentation to stay synchronized. Having this software guide helps everyone understand where we're coming from philosophically, while at the same time orienting people to decisions we've made around [best practices][best-practices-software-guide], [architecture][architecture-software-guide], and [design][design-guide-software-guide].

So read through it once. You don't have to memorize it, but you should definitely have familiarized yourself with everything herein. Trust us -- it will save you time in the long run.

### 2. Set Up Your Environment

Rather than trying to keep this guide up-to-date with all of the changes across all of our various repositories and services, what we recommend is to follow the `README.md` instructions for each of the key services **in this order**. Before you do that though, you've already read this guide in its entirety, right? Especially the [architecture][architecture-software-guide] section, right? **RIGHT?!?!** Good.

So here's the order of operations. If you follow these steps, you _should_ be up and running relatively quickly.

1. [idm][idm-repo]: Identity Management Service
2. [echo][echo-repo]: Echo Service

#### 3. Seed Your Database(s)

Over time, the process by which you do this will change and evolve. But (obviously) before you can do anything with any of our services, you're going to need a user account, since all of our services use a single-sign-on system. How do you do this next step, then?

Find a buddy. Seriously. Head on over to [#phase-4][phase-4-slack], let folks know you've got the services up and running and you need help getting some seed / test data going. That may be an unsatisfying answer, but it's the best we've got right now.


<!-- references -->

[phase-4-slack]: https://learnersguild.slack.com/archives/phase-4

[best-practices-software-guide]: ../best-practices/README.md
[architecture-software-guide]: ../architecture/README.md
[design-guide-software-guide]: ../design-guide/README.md

[idm-repo]: https://github.com/LearnersGuild/idm
[echo-repo]: https://github.com/LearnersGuild/echo
