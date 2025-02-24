# Project Governance


The Kubeadm ignition bootstrap provider for ClusterAPI is a community driven project.
Anyone who wants to participate is welcomed.
We adopted the [CNCF code of Conduct](./CODE_OF_CONDUCT.md) as we pledge to be an opening and welcoming community for anyone who want to participate in it.

The project is governed by a flat hierarchy.
This goverance explains how the project is run.

- [Values](#values)
- [Maintainers](#maintainers)
- [Becoming a Maintainer](#becoming-a-maintainer)
- [Meetings](#meetings)
- [CNCF Resources](#cncf-resources)
- [Code of Conduct Enforcement](#code-of-conduct)
- [Security Response Team](#security-response-team)
- [Voting](#voting)
- [Modifications](#modifying-this-charter)

## Values

The project and its maintainers embrace the following values:

* Openness: Communication and decision-making happens in the open and is discoverable for future
  reference. As much as possible, all discussions and work take place in public
  forums and open repositories.

* Fairness: All stakeholders have the opportunity to provide feedback and submit
  contributions, which will be considered on their merits.

* Community over Product or Company: Sustaining and growing our community takes
  priority over shipping code or sponsors' organizational goals.  Each
  contributor participates in the project as an individual.

* Inclusivity: We innovate through different perspectives and skill sets, which
  can only be accomplished in a welcoming and respectful environment.

* Participation: Responsibilities within the project are earned through
  participation, and there is a clear path up the contributor ladder into leadership
  positions.

## Maintainers

Maintainers have full access to this repository and all included features, like CI, Actions, etc.
Maintainers can merge PRs, approve PR builds+tests, and create and publish releases.
Maintainers collectively manage the project's resources, interact with contributors, elect new maintainers, and remove inactive ones.
The current list of maintainers can be found in [MAINTAINERS.md](./MAINTAINERS.md).
Maintainer access privileges are granted via membership of the Flatcar Github organisation's [iClusterAPI Maintainers team](https://github.com/orgs/flatcar/teams/clusterapi-maintainers).

A maintainer is a contributor to the project's success and a citizen helping
the project succeed.

The collective team of all Maintainers is known as the Maintainer Council, which
is the governing body for the project.

### Becoming a Maintainer

Maintainers are active community members who are responsible for the overall quality and stewardship of the project, and are expected to remain actively involved in the project and participate in voting and discussing of proposed project level changes.

Anyone with an established track record of contributions to the project can become a maintainer.
The contributions are expected to be substantial, and must demonstrate a commitment to the long-term success of the project.
Maintainership is not limited to engineering / development merits.
All contributions - evangelising, facilitating and coordinating, helping with documentation, and similar - are welcome.
Becoming a maintainer is about building trust with the current maintainers of the project and being a person that they can depend on to make decisions in the best interest of the project in a consistent manner.

Maintainer candidates should have demonstrated they:
- Collaborate well.
- Have a deep and comprehensive understanding of the code base, technical goals, and directions (for engineering contributions).
- Actively engage with major feature proposals and implementations.
- Consistently advocate and evangelise the project.
- Facilitate and coordinate community tasks and processes, host and conduct sync meetings, engage with contributors and users.

Periodically, the existing maintainers curate a list of contributors that have shown regular activity on the project over the prior months.
A nominating maintainer will create an issue to propose the new maintainer.
It is recommended to describe the reasons for the nomination and the contribution of the nominee in the issue.
Upon consensus of incumbent maintainers, the issue will be approved and the new maintainer added to the Maintainers team on github.

A Maintainer may be added by a simple majority vote of the existing maintainers.

### Removing a Maintainer

Life priorities, interests, and passions can change.
If you're a maintainer but feel you must remove yourself from the list, inform other maintainers that you intend to step down, and if possible, help find someone to pick up your work. 
At the very least, ensure your work can be continued where you left off.
After you've informed other maintainers, create an issue to remove yourself from the [MAINTAINERS](MAINTAINERS.md) file, or ask a fellow maintainer to do so.
If applicable, file a PR to [EMERITUS_MAINTAINERS](EMERITUS_MAINTAINERS.md) to add yourself to the list of emeritus maintainers.
This will ease your return to active maintainership in the future.

Maintainers may also be removed after being inactive, failure to fulfill their 
Maintainer responsibilities, violating the Code of Conduct, or other reasons.
Inactivity is defined as a period of very low or no activity in the project 
for a year or more, with no definite schedule to return to full Maintainer 
activity.

A Maintainer may be removed at any time by a 2/3 vote of the remaining maintainers.

Depending on the reason for removal, a Maintainer may be converted to Emeritus status.
Emeritus Maintainers will still be consulted on some project matters, and can be rapidly returned to Maintainer status if their availability changes.

## Code of Conduct

[Code of Conduct](./code-of-conduct.md) violations by community members will be discussed and resolved on a private chat on the Kubernetes Slack.
If a Maintainer is directly involved in the report, the Maintainers will instead designate two Maintainers to work
with the CNCF Code of Conduct Committee in resolving it.

## Voting

While most business is conducted by "[lazy consensus](https://community.apache.org/committers/lazyConsensus.html)", 
periodically the Maintainers may need to vote on specific actions or changes.
A vote can be taken on the private Maintainers Slack chat on the Kubernetes Slack.
Votes may also be taken publicly at Fortnightly sync calls.
Please refer to the [Agenda / Minutes doc](https://docs.google.com/document/d/12v6NFr7xal9RH3GEB_1IR6HENq2GMuzALS3l5elvrMg/) for more information.
Any Maintainer may demand a vote be taken.

Most votes require a simple majority of all Maintainers to succeed, except where otherwise noted.
Two-thirds majority votes mean at least two-thirds of all existing maintainers.

## Modifying this Charter

Changes to this Governance and its supporting documents may be approved by 
a 2/3 vote of the Maintainers.
