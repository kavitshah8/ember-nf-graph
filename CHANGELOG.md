- 1.0.0-beta.10
  - FIX [#44](//github.com/Netflix/ember-nf-graph/issues/44) remove nf-scroll-area, which was leftover from splitting out nf-table
  - FIX [#41](//github.com/Netflix/ember-nf-graph/issues/41) fix assertion error that was caused in certain tracking modes
  - FIX [#16](//github.com/Netflix/ember-nf-graph/issues/16) patched addClass so Ember will actually update classes on SVG elements using classNameBindings
  - UPDATE [#38](//github.com/Netflix/ember-nf-graph/issues/38) Test on multiple Ember versions
- 1.0.0-beta.9
  - FIX [#16](//github.com/Netflix/ember-nf-graph/issues/16) SVG classes not swapping when selection changed
  - FIX lock to rx-ember 0.2.5-1
  - FIX [#24](//github.com/Netflix/ember-nf-graph/issues/24) SVG lines no longer complain when nf-vertical-line or nf-horizontal-line have null values
    or return a pixel value less than zero
- 1.0.0-beta.8
  - [CRITICAL BUGFIX] Moved babel to `dependencies` so our addon is actually transpiled in host apps #34
- 1.0.0-beta.7
  - Do not use.
- 1.0.0-beta.6
  - UPDATE [#4](//github.com/Netflix/ember-nf-graph/issues/4) add block params to axis components.
  - FIX [#29](//github.com/netflix/ember-nf-graph/issues/29) remove sad panda rename warning.
- 1.0.0-beta.5
  - UPDATE name to ember-nf-graph
  - FIX [#28](//github.com/netflix/ember-nf-graph/issues/28) Remove a few additional prototype functions. But also I had to 
    remove the addon that removed the prototype functions. (prototype functions are back for now).
- 1.0.0-beta.4
  - DEPRECATE [#11](//github.com/netflix/ember-nf-graph/issues/11) Add warning message that name will be changing from ember-nf-graph 
    to ember-nf-graph for next version
  - FIX [#8](//github.com/netflix/ember-nf-graph/issues/8): Removed prototype functions (e.g. `function() {}.property()`).
  - UPDATE [#3](//github.com/netflix/ember-nf-graph/issues/3): [Examples are now live](//netflix.github.io/ember-nf-graph-examples/dist) special thanks to [@jeff3dx](//github.com/jeff3dx) 
    for all of his hard work!
  - FIX [#25](//github.com/netflix/ember-nf-graph/issues/25): removed tabs in favor of spaces
  - UPDATE rx-ember to 0.2.4, clean up bower.json
  - FIX [#17](//github.com/netflix/ember-nf-graph/pull/17): stop publishing tmp and dist to npm
  - FIX [#21](//github.com/netflix/ember-nf-graph/issues/21): remove leftover console.debug statement
- 1.0.0-beta.3
  - FIX [#9](//github.com/netflix/ember-nf-graph/issues/9): Blueprints now properly named
- 1.0.0-beta.2
  - FIX Update license
  - FIX updated documentation and removed document cruft
  - UPDATE: added a changelog :P
  - META: made meta joke in changelog with appropriate emoticon
- 1.0.0-beta.1
  - UPDATE: just releasing to public
