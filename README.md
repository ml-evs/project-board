# Project board automation

This repo contains a simple workflow to automate adding any assigned issue or PR
across any repository to a personal project board (not a repository project
board).

The items are added with "No status" as setting a status requires some overkill
usage of the GraphQL API.

You should just need to set the right permissions on a "classic" GH token and get the correct project number to write to (note: this is mutable if you delete other projects).
