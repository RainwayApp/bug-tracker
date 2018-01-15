# Rainway Bug Tracker

If you've found an issue with Rainway here's how to report the problem.

### How to file a bug

1. Go to our [issue tracker on GitHub](https://github.com/RainwayApp/bug-tracker/issues)
2. Search for existing issues using the search field at the top of the page
3. File a new issue including the info listed below
4. Thanks a ton for helping make Rainway higher quality!

_**When filing a new bug, please include:**_

- **Descriptive title** - use keywords so others can find your bug (avoiding duplicates)
- **Steps** to trigger the problem that are specific, and repeatable
- **What happens** when you follow the steps, and what you expected to happen instead. Include the exact text of any error messages if applicable (or upload screenshots).
- **Did this work in a previous version?** If so, also provide the version that it worked in.
- **OS version**
- **Extensions?** Any browser extensions you might have installed.
- **Any errors logged** in your Server.log file.
- **Was the error on a client/app or the server?**

### Requesting a feature

Feel free to file new feature requests as an issue on GitHub, just like a bug. We tag these issues "enhancement" and periodically migrate them onto the feature tracker for you.

# What happens after a bug is filed?

### Bug lifecycle

1. New bug is filed; awaiting review
2. Triaged in bug review -- see below ('last reviewed' tag
3. Developer begins working on it -- bug is tagged 'fix in progress'
4. Developer opens internal pull request with a fix, which must be reviewed.
5. Pull request is merged, and the bug's filer is pinged to verify that it's fixed -- bug is tagged 'fixed but not closed' ("FBNC")
6. Filer agrees that it's fixed -- bug is closed, and its milestone is set to the release the fix landed in

### Bug review

We review all new issues on a regular basis. Several things typically happen as part of review:

- Ping the filer for clarification if needed.
- If the issue is a feature request, we'll tag it 'enhancement'; the issue will be migrated to our feature tracker at a later date.
- Add priority labels (high, medium, low, or none - read more below).
- Add release milestone - typically only if a bug is a "release blocker" or related to features still in progress.
- Add feature area label, and possibly other category labels like 'starter bug' or 'Mac only.' 

Depending on priority, milestone, and other workload, a developer may or may not begin working on the bug soon.

Some bugs may be closed without fixing - see "Hey! My bug wasn't fixed!" below.

### Hey! My bug wasn't fixed!

Yeah, what's up with that? There are a number of reasons an issue might get closed without being fixed:

- Tagged 'enhancement' - It's not forgotten! Look for a link in the comment thread to our feature backlog. Please vote on the issue (thumbs up/down) to help us prioritize it!
- Tagged 'fixed but not closed' - We think it's fixed. Make sure you have a Rainway build containing the fix (check the milestone assigned to the bug). If you're still seeing it, let us know.
- Duplicate - There's already a bug for this.
- Unable to reproduce - We're unable to reproduce the result described in the bug report. If you're still seeing it, please reply with more detailed steps to trigger the bug.
- Out of scope - This change probably doesn't belong in Rainway.
- Not a bug / fact of life - This is the intended behavior. If it feels wrong, we should discuss how to improve the usability of the feature.

If you disagree with a bug being closed, feel free to post a comment asking for clarification or re-evaluation. The more new/updated info you can provide, the better.

### Responsible Disclosure Procedure

Do not report security issues on our public issue tracker. 

We at Rainway take user security very seriously, which is why it is very important for us to make it as easy and clear as possible for people to alert us to potential security concerns. The proper procedure should you find such a bug is as follows:

1. Write an email detailing the precise nature of the vulnerability.
2. Encrypt your message with our [PGP public key](https://rainway.io/rainway.pgp).
3. Send it to security@rainway.io

We will respond to you as soon as possible, likely within 24 hours. If we have any further questions, expect a response back.

We encourage everyone interested in submitting a disclosure to read the [IETF’s “Responsible Vulnerability Disclosure Process”](https://tools.ietf.org/html/draft-christey-wysopal-vuln-disclosure-00) and follow the guidelines and principles within.

Depending on the severity and scale of the vulnerability, you may (at your discretion) be recognized for your work. We are not offering monetary compensation at this time. All reports are subject to a 30 day embargo for user safety.
