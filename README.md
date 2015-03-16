This just works around https://github.com/npm/npm/pull/7627 and the fact that dropbox.js (A) requires prepublish in order to build its library and (B) isn't merging https://github.com/dropbox/dropbox-js/pull/183 by publishing a compiled snapshot that incorporates the Browserify fix.

This repo can go away once either of those PRs is merged.
