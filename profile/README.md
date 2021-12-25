Inspired by the original [gh:mahmoud/boltons][1] GitHub repository /
[boltons][3] PyPI package (founded ~10 years ago), this organization takes a
modern approach to solving the same problem.  Namely, while we strive to adhere
(more-or-less) to the design tenets of the original project, we choose to
utilize separate GitHub repositories and separate PyPI packages for each
cohesive set of library utilities.

The original project's architecture statement can be found [here][2]; we
summarize the design tenets found on that page below:

1. Be pure-Python and as self-contained as possible.
1. Perform a common task or fulfill a common role.
1. Demonstrate and mitigate some insufficiency in the standard library.
1. Strive for the standard set forth by the standard library by striking a
   balance between best practice and “good enough”, correctness and common
   sense. When in doubt, ask, “what would the standard library do?”
1. Have approachable documentation with at least one helpful doctest, links to
   relevant standard library functionality, as well as any 3rd-party packages
   that provide further capabilities.

Here is another quote from the Architecture document of the original boltons
project:

> The larger the problem solved, the less likely the functionality is suitable
> for inclusion in boltons; boltons are fundamental and self-contained, not
> sweeping and architecture-defining.

In the python-boltons (AKA "big boltons") organization, we still believe that
every bolton in this organization should be _fundamental and self-contained_.
Moreover, we largely support the statement quoted above as a whole. With that
said, one of the benefits of breaking each bolton out into its own repository
is that it makes it easier to scale these utility libraries to higher levels of
abstractions; we shall allow this to occur organically and will not cripple
library growth for the sake of keeping the library "small".

For more information on the design of this organization, refer to the documents
in this organization's [design][4] repo, which we consider to be mandatory
reading for anyone interested in contributing / maintaining boltons.


[1]: https://github.com/mahmoud/boltons
[2]: https://boltons.readthedocs.io/en/latest/architecture.html
[3]: https://pypi.org/project/boltons/
[4]: https://github.com/python-boltons/design
