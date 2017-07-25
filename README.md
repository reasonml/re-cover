# Reason Conversion Coverage Visualizer

This small script generates a visualization of your codebase's conversion progress from JavaScript to Reason.

**This is just a proof of concept**. It only works when called just outside a flat `src` directory.

## Installation & Usage

Clone this directory and invoke the `re-cover` script at the root of the project, where a flat `src/` resides. You can then open `comp.svg` in a browser, or `comp.dot` with a dotty visualizer such as GraphViz.

## Prerequisite
**Note**: doesn't work on Windows yet. Contribution welcome!
You need to have GraphViz installed for the `dot` utility, and the usual `sed, find, grep`.

## Example
![Example](/example/comp.png)
