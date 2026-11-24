# Chatter3

**Chatter3** is a free 1-on-1 English conversation app. You press a button,
another learner is put in front of you, and you talk for five minutes. No
payment, no subscription, no token.

* **The app:** <https://app.chatter3.com>
* **Engineering notes:** <https://chatter3-lab.github.io> — six production bugs
  in a WebRTC app, what caused each one, and the test that keeps it fixed
* **Open source:** [`chatter3-call-clock`](https://github.com/chatter3-lab/chatter3-call-clock)
  — the call timer, extracted because it is small, self-contained, and the kind
  of thing every video-call app gets wrong. MIT, no dependencies, also on
  [npm](https://www.npmjs.com/package/chatter3-call-clock).
* **The same six bugs, written up as articles:**
  [dev.to](https://dev.to/chatter3_lab/six-production-bugs-in-a-webrtc-app-with-the-tests-that-keep-them-fixed-25oj) ·
  [Hashnode](https://hashnode.com/posts/six-production-bugs-in-a-webrtc-app-with-the-tests-that-keep-them-fixed/6afd4846d442bab38e0895c0) ·
  [Medium](https://medium.com/@chatter3_lab/six-production-bugs-in-a-webrtc-app-with-the-tests-that-keep-them-fixed-aef40ace1c3a)

## Why the notes are public

Every bug in that list was found by a person, not by a test: the call that
ran for the wrong number of seconds, the clock that was seven seconds fast
on one phone and slow on the other, the session that was charged for a
partner who never came. The write-ups are here so that anyone building a
video-call app can copy the tests instead of the bugs.

## Repositories

| | |
|---|---|
| [`chatter3-lab.github.io`](https://github.com/chatter3-lab/chatter3-lab.github.io) | The engineering notes, served by GitHub Pages |
| [`chatter3-call-clock`](https://github.com/chatter3-lab/chatter3-call-clock) | The call clock, published on npm as `chatter3-call-clock` |

The app itself is not open source.
