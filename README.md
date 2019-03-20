# Pareto Network Development Activity Relay

<p align="center">
  <img src="Pareto-Logo.png" />
</p>


<img src="https://status.pareto.network/badges/badge_commit.svg"></img>
<img src="https://status.pareto.network/badges/badge_contributors.svg"></img>
<img src="https://status.pareto.network/badges/badge_open_issues.svg"></img>
<img src="https://status.pareto.network/badges/badge_closed_issues.svg"></img>
<img src="https://status.pareto.network/badges/badge_closed_pull_request.svg"></img>
<img src="https://status.pareto.network/badges/total_lines_code_without_dependencies.svg"></img>
<img src="https://status.pareto.network/badges/total_lines_code_with_dependencies.svg"></img>
<img src="https://status.pareto.network/badges/badge_member_count.svg"></img>
<img src="https://status.pareto.network/badges/badge_member_count_announcements.svg"></img>
<img src="https://status.pareto.network/badges/total_community.svg"></img>
<img src="https://img.shields.io/twitter/follow/ParetoNetwork.svg?style=plastic"></img>

This is a public service to show real time and historical activity of the Pareto Network project. Primarily it pulls in github commits from private internal codebase repositories - which the community cannot see - and posts the commits in a public repository.

Discuss project activity in our [Telegram Chat](https://t.me/paretonetworkdiscussion)

## Background

Projects that involve the cryptocurrency communities are frequently judged by the number of github commits they have, to determine their health or even overall legitimacy. This metric only works if the organization is using public github repositories, whereas a more common business practice involves private repositories. Many external services look at this metric, so as an organization with private repositories we can address this misalignment with the relay. This relay also pulls in information from our public repositories. This relay helps include community participants.

## How to use

A log file is created for every commit from every repository in the Pareto Network organization. For example

`2018-02-22 22_34_50-ParetoNetworkServer.git-master-08e153a483b257580ad837eb9ef5f990fa4a9fe1.log`

This tells you the date and time: `2018-02-22 22_34_50`

The project which was being worked on: `ParetoNetworkServer.git`

The branch of the project that was modified: `master`

The commit hash: `08e153a483b257580ad837eb9ef5f990fa4a9fe1`

and within every log file, a little more information is included, for example:

> commit 08e153a483b257580ad837eb9ef5f990fa4a9fe1

> Author:	Eric Lamison-White <eric@blockology.org>

> Date:	Thu Feb 22 2018 17:34:50 GMT-0500 (Colombia Standard Time)

>    .gitignore


The final line including some of the files that were modified.

With this information the community and researchers can get insight into what was modified.
