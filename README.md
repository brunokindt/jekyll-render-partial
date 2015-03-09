# Jekyll Render Partial Tag

A jekyll plug-in that import files any renders them inline. The plugin
is a copy of
[octopress render partial](https://github.com/imathis/octopress/blob/master/plugins/render_partial.rb) with a few lines removed to make it work under Jekyll.

## Installation
- Copy render_partial.rb to your Jekyll `_plugins` directory

## Usage:
- e.g. `{% render_partial assets/graph.svg %}
- e.g. `{% render_partial partial/stuff.md %}

