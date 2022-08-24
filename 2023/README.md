# Interop 2023

Interop 2023 is an effort to make the web more interoperable in key areas, prioritized by web developer and user needs. The team behind it is formed of browser vendors and other contributors to the web platform, and is part of [the web-platform-tests project](https://github.com/web-platform-tests/wpt).

Similar to [Interop 2022](https://wpt.fyi/interop-2022), this will be a public metric based on the progress of selected focus areas and investigation efforts. The overall timeline for the planning process is:

- Public call for proposals beginning September 15.
- Proposal review by the team, with an opportunity for refinement.
- Selection of proposals by the team, based on consensus.
- Public launch in early 2023.

If you would like to make a proposal or contribute in other ways, read on.

## Making a proposal

If you've had problems using a feature on the web because of differences between browsers, or because it isn't implemented in all browsers, it may be a good proposal for Interop 2023!

Before making a proposal, here's what to expect:

- Only features which have high quality specifications and tests are in scope. Interop 2023 is not a venue for specifying new features, that work happens in working groups at the W3C, WHATWG, etc.
- Interop 2023 is not a process for making browser vendors work on things they're opposed to. Decisions are made by consensus, so highly contentious features are unlikely to be accepted.
- Even great proposals may ultimately not be accepted, since we have to prioritize.

The process for making and driving a proposal is:

- September 15 to October 15: [File a proposal issue](https://github.com/web-platform-tests/interop/issues/new?assignees=&labels=proposal&template=proposal.md) and fill in as many details as you can. There is no required part of a rationale, but a few dimensions to consider are:
  - Web developer sentiment from polls or surveys, e.g., [MDN surveys](https://insights.developer.mozilla.org/) or [State of CSS](https://stateofcss.com/).
  - Browser bugs or browser bug statistics, e.g., [Chromium](https://bugs.chromium.org/), [Gecko](https://bugzilla.mozilla.org/), [WebKit](https://bugs.webkit.org/).
  - Current usage of the feature, e.g., [Chrome use counters](https://www.chromestatus.com/metrics/feature/popularity) or [HTTP Archive](https://httparchive.org/). 
- October 16 to October 30: The Interop team reviews proposals, and may ask questions and discuss on the issue. During this time some refinements to the proposal can still be made. After this point no further action is required, but continued participation is certainly welcome.
- November 1 to November 30: The Interop team decides, by consensus, which proposals to accept. Accepted proposals will require a pull request to document the accepted proposal in the repository. Help with this will be appreciated, but not required.

## After a proposal is accepted

The Interop team is responsible for driving everything after a proposal is accepted. Here's what to expect:

- December 1 to December 16: Detailed review of the tests, and possibly writing some additional tests. A public dashboard will be prepared based on all of the accepted proposals.
- January 9 to January 20:
  - Finalize test selection.
  - Complete announcement plans. Prepare dashboard for launch.
- January 23 to January 27: Public launch.
- Throughout 2023: Progress is tracked on the public dashboard. If issues with the test suite are found, anyone can make [test change proposals](https://github.com/web-platform-tests/interop/issues/new?assignees=&labels=test-change-proposal&template=test-change-proposal.md), which will be reviewed by the Interop team. Significant changes to the scope are unlikely to be accepted.

Ultimately, the outcome we hope for is that interoperability significantly improves, and that web developers and users benefit.

## Other ways to contribute

TODO

You're also welcome to join the conversation in the [`#interop2022:matrix.org` Matrix channel](https://app.element.io/#/room/#interop2022:matrix.org)!