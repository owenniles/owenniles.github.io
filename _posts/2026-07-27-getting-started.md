---
title: Getting Started
description: Some thoughts on what makes a good getting started guide.
reading_time: 3
---

For my first blog post, I thought I'd write about getting started.

When I encounter a new codebase for the first time, it's a little scary. There is a lot to look at, and sometimes I don't know where to begin. Once I start poking around, it usually becomes less intimidating. The hard part is finding a good place to start.

A good getting started guide gives me that place. It should help me get my hands dirty with the codebase as quickly as possible, in as few familiar steps as possible.

Think about how easy it was to get started with your coding agent. You ran the install script, started the binary, logged in, and began asking questions. A few minutes later, you probably felt comfortable enough to ask the agent how to configure itself. The path to doing something useful was short enough that curiosity took over before frustration could.

I think getting started with a codebase should feel similar.

For some projects, the guide might begin by showing you how to run the tests. Once you can run them, you can change some code and see what breaks. Trying to understand the broken tests teaches you how the system behaves. Eventually, you understand the tests well enough to write one yourself.

For a service, the guide might show you how to run it locally and make a request against it. Once the request works, you can trace the code that handles it. One component leads to another, and the shape of the service begins to emerge.

Both approaches give you a way to interact with the codebase. They turn a giant, unfamiliar ball of code into something that can answer questions. You have a little leverage now. You can make a change and get feedback.

There is also something reassuring about a good getting started guide. It feels like having a companion while you begin exploring. Someone cared enough to leave you a way in, and wanted you to have a pleasant time reading the code they wrote.

Writing the guide is useful for the people who maintain the codebase, too. It can be a test of the developer experience. If it takes a long list of manual steps to run a test or make a request, that might be a sign that the system is more complicated than it needs to be, or that the developer experience hasn't received enough attention. The guide doesn't create that friction. It just makes the friction difficult to ignore.

This still matters when you're working with a coding agent. An agent can help you find your way around an unfamiliar repository, but it needs a way to check its work. It benefits from the same things you do: a command that runs the tests, a service that starts locally, and a clear signal that something worked.

A getting started guide doesn't need to explain the whole codebase. It just needs to give someone a good place to start.
