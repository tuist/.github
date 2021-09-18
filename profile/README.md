# Tuist

Scaling up Xcode projects is a tedious undertaking: Git conflicts in `.pbxproj` files, slow Xcode, large build times, and brittle projects that break easily when adding/removing targets to its graph.
This often leads to developer frustration, and the companies that can afford it, create infrastructure teams dedicated to mitigate those pains. In few cases, the pain is mitigated with the complexity of alternative build systems like [Bazel](https://bazel.build/).

We believe painless Xcode development with large projects can be **enjoyable** keeping things **simple** and without requiring an **infrastructure team.** Tuist achieves that by leveraging Xcode project generation. It provides an explicit interface in Swift to declare modular projects. Unlike YAML-baed project generators, it can optimize your projects' graph at generation time by removing the unnecessary targets and replacing some of them with their binary counterpart.

**Focus** on building great apps for Apple platforms, and we take care of the rest ❤️.