# monorepo_actions_sandbox

A sandbox where I test the monorepo idea using Github actions

## Goals

- [X] Make releases trigger a publish action
- [ ] Let publish action decide what to build based on tag
- [ ] Create many workflows that build for specific OS
- [ ] Create reusable workflow that will upload specified artifacts to GH release

Workflow:

- [ ] When draft PR is created or pushed to, move associated task to the "In progress" column
- [ ] When all draft PR associated with the task are stale for two days, move the task to the "To Do" column
- [ ] When draft PR becomes normal PR, move to "Code review" column
- [ ] When normar PR gets all N necessary reviews, move to "Testing" column
- [ ] Need to think about this, but, maybe if somebody from the tester group approves PR, move to "Ready for merge" column... or merge automatically
- [ ] On merge, move associated task to "To be released" column
- [ ] On publish move all tasks associated with merged PR to the "Relaesed" column
- [ ] Populate release artifacts
