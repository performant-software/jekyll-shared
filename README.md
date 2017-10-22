# jekyll-shared

A way to more easily maintain shared code (like search) across all the jekyll sites present and future, and also a mechanism to run some “preflight” on each site.

These scripts also assume the dev machine is a mac (more specifically they assume default locations for various utilities) although nothing is particularly exotic and any linux system with bash should work with minor tweaks. I assume it will also work with windows machines and cygwin or similar.

To use:

1. Clone this repo alongside the other jekyll repos, into a folder called ‘jekyll-shared’

2. Put a “preflight” script into each repo (example in the shared repo). Run it.
