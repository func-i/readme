# FI readme

Docs for FI.

## process

### [trello](https://trello.com/functionalimperative)

Devs are responsible for Trello management. Usual columns:

* Milestones (client or internal due dates, no feature/bug tickets here)
* Assets (SOWs, wireframes, design specs, no feature/bug tickets here)
* Backlog
* Todo
* Sprint
* Doing
* Pending Merge
* Done
* Staging
* Prod

### [harvest](https://functionalimperative.harvestapp.com)

All development + meeting time should be tracked in Harvest.

It's common for juniors to shortchange time tracked due to concern that they're spending more time than they "should." This is wrong. Track all time.

### git/[github](https://github.com/func-i)

#### branching

FI follows a [git-flow](http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/)-esque branching strategy.

Master is production code. Features and bugs map directly to Trello cards and should be tackled in branches following this convention:

```unix
<type>/<trello_card_num>-<description-using-hyphens>
```

So for Trello card 420—which describes a new feature, full text search—you would create a branch named:

```unix
feature/420-full-text-search
```

#### pull requests

Juniors should not push directly to master without submitting a pull request for their feature or bug branch and its acceptance or merge by the lead for the project.

## maintaining code quality

### dev leads

The dev lead for a project is responsible for its code quality. Sometimes the lead will be the only developer. Sometimes they'll be developing alongside another developer. Sometimes their only relationship with the code base will be through peer reviews and pull requests. But it's still their baby.

### [#helpline](https://funci.slack.com/messages/helpline/)

A useful internal place for questions without answers yet. This prevents DMs to your dev lead from going unnoticed.

### peer reviews

FI-wide peer reviews happen for an hour, once-a-week. You can find the [current schedule here](https://docs.google.com/spreadsheets/d/11Sjxgiet-l6QmKZAPMVogAkPBl6veiQkKQB97QQLru8/edit#gid=0).

Some peer review strategies:

* Code author brings a problem or two to the session, explains how they solved the problem, and why it doesn't quite feel right.
* Author presents his or her Worst Code™ for review.
* Reviewer checks week's commits for interesting or confusing solutions. Discuss.

### twenty-minute rule

If you're stuck on something for twenty minutes, ask for help. It's simple.