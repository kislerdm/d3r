# d3r 0.6.8

### Updates

* `d3_dep_jetpack()` added. Essentially the same as d3_dep_v4(), but with a number of convenience functions added. Learn more by checking out the [d3-jetpack github page](https://github.com/gka/d3-jetpack). 

* update d3v4 to [`4.10.0`](https://github.com/d3/d3/releases/tag/v4.10.0)

# d3r 0.6.7

### API Changes

* **(BREAKING)** d3_table weight column is now named value to be consistent with the newest d3-sankey plugin [commit](https://github.com/timelyportfolio/d3r/commit/65b913322f1a6c71db21496f158bb0bed645a1f6).

* Use unpkg.com for online dependencies

# d3r 0.6.6

### Updates

* add d3_table() function to convert R table into list of a nodes data.frame and a links data.frame modelled after [example](https://gist.github.com/timelyportfolio/3616869996703d48a981)

# d3r 0.6.5

### Updates

* update d3v4 to [`4.9.1`](https://github.com/d3/d3/releases/tag/v4.9.1)

# d3r 0.6.4

### Bug Fix

* d3_nest would fail with certain hierarchies that had multiple NA level; fix only takes first na_child since non-first children will be duplicates (see [commit](https://github.com/timelyportfolio/d3r/commit/1529acad5230207e3b4711202509bc5e9411076b))

# d3r 0.6.3

### Updates

* update d3v4 to [`4.8.0`](https://github.com/d3/d3/releases/tag/v4.8.0)
* test with development `dplyr`

# d3r 0.6.2

### Updates

* update d3v4 to [`4.6.0`](https://github.com/d3/d3/releases/tag/v4.6.0)
* add `d3_v8()` convenience function to return `V8` context with d3.js loaded

# d3r 0.6.1

### Updates

* update d3v4 to [`4.4.4`](https://github.com/d3/d3/releases/tag/v4.4.4)

# d3r 0.6.0

### Updates

* add `colname` to return value (see [commit](https://github.com/timelyportfolio/d3r/commit/5787e03a6b59c89b367a88f16e9c5a899482a8d3))

* improve `NA` child promotion for deeply nested hierarchies

### API Changes

* **(BREAKING)** change `id` to `name` (see [issue]( https://github.com/timelyportfolio/d3r/issues/10))

# d3r 0.5.0

### Updates

* update d3 to [4.4.0](https://github.com/d3/d3/releases/tag/v4.4.0)

### API Changes

* (non-breaking) add offline argument to d3_dep_v3 and d3_dep_v4


# d3r 0.4.2

* CRAN release

