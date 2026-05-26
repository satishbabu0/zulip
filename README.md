# Zulip Open Source Contribution

Zulip is one of the world’s largest open-source team chat platforms, designed to make communication more organized and productive through its unique topic-based conversation system. It combines the advantages of email-style threading with modern real-time chat, making it widely used by companies, developers, research groups, and open-source communities around the world.

As part of exploring large-scale open-source development, I contributed to the Zulip project by working on the Jira webhook integration system built with Python and Django.

## My Contribution

I worked on fixing a formatting issue in Zulip’s Atlassian Jira integration where Markdown formatting rules were incorrectly applied inside Jira `{code}` and `{noformat}` blocks during webhook processing.

### What I implemented

* Preserved raw code block formatting during Jira markup conversion
* Prevented unintended Markdown transformations inside literal code sections
* Added regression tests for the Jira webhook processing flow
* Ran backend test suites locally and verified webhook behavior

## Technologies Used

* Python
* Django
* Git & GitHub
* Webhooks
* Backend testing
* Open-source collaboration workflow

## What I Learned

Through this contribution, I gained hands-on experience with:

* Large-scale open-source project architecture
* Backend debugging and webhook parsing
* Writing and running regression tests
* Git branching, pull requests, and code review workflows
* Collaborating within an active developer community

## Pull Request

PR Title: `jira: Preserve formatting inside code blocks`

This contribution helped me better understand how real-world integrations and production-grade backend systems are designed and maintained in modern software engineering projects.
