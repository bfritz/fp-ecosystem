To the Scala community:

Hallway debate at last year's inaugural Typelevel Summit focused on the problem of supporting existing users while introducing library support for Cats. There were no obvious answers. Over the past year we have experimented with shims, preprocessors, and manually maintained forks. Although we had some success, we concluded that none of these strategies are sustainable. Each introduces impediments to contributors, complexity to end users, or both.

Fortunately, the maturing of Cats in the past year and the vibrancy and quality of its rapidly growing ecosystem indicate a clear way forward. The maintainers of the following projects intend to standardize on Cats as a direct dependency and phase out alternate builds.

* [doobie](https://github.com/tpolecat/doobie)
* [http4s](https://github.com/http4s/http4s)
* [Matryoshka](https://github.com/slamdata/matryoshka)

Each project will act on its own schedule with the goal of clean interoperability with Cats and one another by mid-to-late 2017. We invite other projects to follow our lead.
