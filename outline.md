Where we have been:
  - TDD
  <!-- - brittle specifications -->
  <!-- - developers and non-developers don't see problems the same -->
Where we are:
  - BDD
  - code coverage
  <!-- - dev's and non-dev's don't see eye to eye still -->
Where we can go:
  - The immediate future:
    - BDD + language agnosticism (tests AS data) (show node-jsmin-sourcemap as sample)

How does this impact me?

Getting the right balance of code coverage
  - Taking it too far
  - Tests should never repeat each other
  - BDD creates a very nice amount at 70% (link article)

TODO: Don't forget about Human Schema

Attribution: @fat and mustache js


// TODO: I forgot LANGUAGE agnostic on my submission ;_;

// TODO: Should we include the TDD as data discussion?

// TODO: Don't forget notes on how fucking subtle the .next part is

// TODO: When convert into HTML, update closing title slide URL

*****************

Submitted to JSConf 2013

# Making programming normal
## A dialog on changes from TDD to BDD and what lies in the future.

The main nerdgasming points are:
- We can make tests purely data (e.g. JSON)
    - Makes everything test framework agnostic (swap between mocha, vows, and jasmine freely)
    - Much DRYer tests themselves (common assertions are easily abstracted away)
- Faster translation from language process
- Code coverage worries and lengthy test maintenance dissolves
    - You test only what you are going to be using