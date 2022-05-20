# TypeScript Concave Hull

This is a  TypeScript implementation of the concave hull algorithm [described in Park and Oh (Journal of Information Science and Engineering, 2012)](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.676.6258&rep=rep1&type=pdf). This code base was derived from a Javscript implementation of the above algorithm, _concaveman_, [which can be found at this repo](https://github.com/mapbox/concaveman).  

Several of the _concaveman_ dependencies were also hand-ported to TypeScript.  So, you will see _RBush_ [https://www.npmjs.com/package/rbush](https://www.npmjs.com/package/rbush) renamed and ported as _RTree_ in the current implementation.  The current _RTree_ implementation is not templatized; it is optimized for use in the concave hull algorithm.

NOTE:  This repo is no longer active.  The Concave Hull has been updated and moved to [the AMYR Library](https://github.com/theAlgorithmist/AMYR).  This repo is left open for historical purposes.

Author:  Jim Armstrong - [The Algorithmist]

@algorithmist

theAlgorithmist [at] gmail [dot] com

Typescript: 3.8.3

Jest: 25.2.1

Version: 1.0

## Installation

Installation involves all the usual suspects

  - npm installed globally
  - Clone the repository
  - npm install
  - get coffee (this is the most important step)


### Building and running the tests

1. npm t (it really should not be this easy, but it is)

2. Standalone compilation only (npm build)

Specs (_hull.spec.ts_) reside in the ___tests___ folder.


### Notes

This is a beta implementation of the TypeScript port.  The goal is to produce an implementation with well-defined typings for all variables and to work in an Angular environment with strict null checks.

Expect the code to be incrementally updated over time.  It will also be compiled with TypeScript 4.0+ in a future release.


License
----

Apache 2.0

**Free Software? Yeah, Homey plays that**

[//]: # (kudos http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

[The Algorithmist]: <https://www.linkedin.com/in/jimarmstrong/>

