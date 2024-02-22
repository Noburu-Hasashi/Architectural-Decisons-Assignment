# Data Storage

## Status
This decision is currently being proposed.

## Context
The university's ask is that we need our app to be able to access and perhaps manipulate their already built Active Directory System. Since we need our application to be used offline as well, we would need to keep all the necessary data handy for the user.

## Decision
Using a mix of both offline(local) database system such as SQLite and an online database, perhaps more accessible to professors such as Firebase.

## Consequences
Data stored locally could have some security concerns, but they can be taken care of by just using the database stored locally as just a copy referencing the original database which would be the one stored online. This all can be quite challenging for the developers, which also adds to the consequences.