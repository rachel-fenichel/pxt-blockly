# Blockly (Microsoft MakeCode fork)

This is a fork of [Blockly](https://github.com/google/blockly/), an open source visual programming environment.
The fork is maintained by the Microsoft MakeCode team, and is used to power the blocks environment in [PXT](https://github.com/Microsoft/pxt).


Major additions and changes in this fork:
* [scratch-blocks](https://github.com/llk/scratch-blocks) rendering of the blocks [block_render_svg.js](https://github.com/Microsoft/pxt-blockly/blob/develop/core/block_render_svg.js)
* Using insertion markers instead of dragged connections [insertion_marker_manager.js](https://github.com/Microsoft/pxt-blockly/blob/develop/core/insertion_marker_manager.js)
* Inverted and coloured toolbox modes [toolbox.js](https://github.com/Microsoft/pxt-blockly/blob/develop/core/toolbox.js#L428) 
* Supports disabled categories [toolbox.js](https://github.com/Microsoft/pxt-blockly/blob/develop/core/toolbox.js#L360)
* Supports icons in the toolbox
* Adds a number slider field [field_slider.js](https://github.com/Microsoft/pxt-blockly/blob/develop/core/field_slider.js)
* Zoom in / out with touch gestures [touch_gesture.js](https://github.com/Microsoft/pxt-blockly/blob/develop/core/touch_gesture.js)
* Workspace comments that appear like sticky notes [workspace_comment.js](https://github.com/Microsoft/pxt-blockly/blob/develop/core/workspace_comment.js)
* A number of Edge & IE fixes
* Support underlining and icons in flyout labels [flyout_button.js](https://github.com/Microsoft/pxt-blockly/blob/develop/core/flyout_button.js#L203)

## Prerequisites

* node, npm
* python

## Development

* `git clone https://github.com/Microsoft/pxt-blockly`
* `cd pxt-blockly`
* `npm install .`

## Building

* `gulp build` to build blockly

## Playground

There is a playground manual testing page at [tests/playground.html](./tests/playground.html), which requires no build step or server running.

`open tests/playground.html`

## License

The original Google/Blockly is licensed under Apache License (Version 2.0).

New code is licensed under MIT.
