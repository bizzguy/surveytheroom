# Survey the Room

Ask a room full of phones a question from a conversation with Claude. Claude puts the question
on every phone, people answer, and the results appear on the shared screen as they arrive.

This plugin adds two things:

- The Survey the Room connector (`https://surveytheroom.com/mcp`). You sign in with your email
  address the first time Claude uses it.
- A skill that teaches Claude how to run a session: create a room, ask questions, run votes,
  sort typed answers into themes, and end with a report.

## Install

In Claude Code:

```
/plugin install surveytheroom --marketplace bizzguy/surveytheroom
```

Then say: "Create a room and ask what we should build next." Claude opens the sign-in page the
first time. Other ways to connect, including Claude on the web: surveytheroom.com/connect.

## What it sends

The questions you ask Claude to publish, and your requests to read answers and results, go to
surveytheroom.com. Answers typed by your audience come back to Claude so it can show and sort
them. Nothing else from your conversation is sent.

A Survey the Room account is needed. Plans: surveytheroom.com/pricing. Help: surveytheroom.com/help.
Privacy: surveytheroom.com/privacy. Support: support@surveytheroom.com.

Copyright (c) 2026 XoSelf LLC. All rights reserved. See LICENSE.
