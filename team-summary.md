# Moment.js Summary Page

## Issues we thought about

### [Locale Issue in Catalan](https://github.com/moment/moment/issues/4508)
* Dan commented on this issue, and sparked a discussion on the thread.
* Different languages have different ways of showing dates (May 5th versus cinco de mayo)
* One function was providing the date '4 de maig' but then when you would verify that that was the correct version for that format, it would return false
* While dealing with different languages seemed fun, moment has stricter guidelines on who can fix locale issues.
* Despite the fact that we couldn't work on this, the community validated the thought we put into the issue.
### [DST Transition Issue](https://github.com/moment/moment/issues/4506)
* We were unable to replicate this issue, the same with other members of the community.
* Issue was closed due to this fact, so we were unable to work on it. 
### [Relative Time Threshold](https://github.com/moment/moment/issues/4514)
* The issue we actually decided to work on. 
* We thought that adding a feature would be more fun than fixing a bug.


## Pull Requests
### [Added support for weeks in relativeTimeThreshold()](https://github.com/moment/moment/pull/4570)
* Current state: open
* We pass all the tests, and have recieved feedback. Moderator said our code looked good, just waiting on them to merge the code.
* Everyone in the group contributed to this PR, as it was the main issue we worked on. 

### [Documentation for the PR above](https://github.com/moment/momentjs.com/pull/507)
* Jason added this after we submitted the PR, so there would be docs for it upon merging. 

## Commits by Member (omitting simple typo fixes, etc):

### Lauren
* [./locale vs ../locale](https://github.com/nyu-ossd-s18/moment/commit/40a15a0fc92fd6bd0a62365e9a456e4de76b6987)
* [Fixed thresholds for days and weeks](https://github.com/nyu-ossd-s18/moment/commit/d023e5c98a20f0ca60c6ea801fb72dd0196843df)
* [Fixed Relative Time Test](https://github.com/nyu-ossd-s18/moment/commit/446a657c12e99f562db02089f1003854e4364a32)
* [More accomodation for weeks in tests](https://github.com/nyu-ossd-s18/moment/commit/7ea848cd0e09e77395eca00fff5cabe8f3b0d939)
* [Added more tests for default values](https://github.com/nyu-ossd-s18/moment/commit/f4d96906ce72a2a754b0ba9a9ab0dc075b83cfba)
* [More Tests](https://github.com/nyu-ossd-s18/moment/commit/c62bdfee3762ec82040e3c9c2ae052a30af07342)
* [Update our fork to present day fork for PR](https://github.com/nyu-ossd-s18/moment/commit/0c441d7b5bf5c377dbf121a22e334542b513ac56)
### Dan
* [Init for weekly relative time](https://github.com/nyu-ossd-s18/moment/commit/b9cacda8b8a1d654e181a1471abd1e273a860df7)
* [Rolled back laurens bad PR](https://github.com/nyu-ossd-s18/moment/commit/a7b6425873d56c17e55b482e29833e1c8ef7038e)
* [Change order of weeks and months](https://github.com/nyu-ossd-s18/moment/commit/5e3083a3e3f1f9fffeebc1afa0da530d218f3536)
* [Fixed transform test](https://github.com/nyu-ossd-s18/moment/commit/05e0f020dd205e9fe775a6935606c2bba08bc3cb)
### Jason
* [Default Relative Time](https://github.com/nyu-ossd-s18/moment/commit/3f0b159ccf0ca94cd084a725708a5aed3783347f)
* [added plural weeks](https://github.com/nyu-ossd-s18/moment/commit/0dc49afd458298ff09ca67e3acbc8e6b42ed3572)
* [added formatting and changed day threshold](https://github.com/nyu-ossd-s18/moment/commit/cf0d06b10670f7d39c0e0e1b498ab8554b2688c1)
* [Fixed String Format](https://github.com/nyu-ossd-s18/moment/commit/2ec6702b05944dc1eeccd5b16d0ce31bc9c9abc7)
### Felix
* [Changed humanize tests](https://github.com/nyu-ossd-s18/moment/commit/b9710169e0e14215a7cc0562f7ecadada0574ba6)
* [Added more tests](https://github.com/nyu-ossd-s18/moment/commit/476f8616f9101f0368bb74df4e4384f4d8c937c5)
* [Test Fixes](https://github.com/nyu-ossd-s18/moment/commit/74dfde1566d0b4e199840df0e89b0ee2e662b655)
* [More Fixes](https://github.com/nyu-ossd-s18/moment/commit/37315c3f8c0f102d40c4b57a0e9fee1ade815743)
