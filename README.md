# wordtown

Building out a game prototype.

## Goals

My current goal is to practice building out a set of webpack skills that will help me grow as a front end developer.

### What does Webpack Do?

- Bundles code efficiently
- Creates a hot-reloading run-time environment

## Notes

### Webpack:

- Script <Top down bottom execution>
- 2 ways to execute in the browser
  - src in a script tag
  - write iin script tag

#### Challenges:

- Doesn't scale well at all.
- HTTP 2 doesn't help very much (30 - 50), application might have 1000s and 1000s of modules to build out a specific application.
- JS Has everything global (including functions and objects)

IIFE: Immediately Invoked Function Expression

- ohhh, is this how webpack modularizes the scope?
- apparently no. These are incredibly slow.

#### Module Bundler:

- Specifically designed for the browser
- supports static async bundling
  - apparently this is a profound shift for static code analysis

#### Goals:

- To be able to build my own webpack config from scratch to include Vue, React etc.
