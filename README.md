# 🧱 Masonry Bricks

Mason templates for boilerplate reduction.  For help using Mason, see their documentation [here](https://github.com/felangel/mason/tree/master/packages/mason_cli#readme).

## Getting started 🚀

### Install locally 🏠

To install one or more bricks locally, add them to your directory's `mason.yaml`:

```yaml
bricks:
  <BRICK_NAME>:
    git:
      url: https://github.com/KhaosArbiter/masonry
      path: bricks/<BRICK_NAME>
```

### Install globally 🗺

To install one or more bricks globally, use the following command:

```sh
$ mason i https://github.com/KhaosArbiter/masonry --path bricks/<BRICK_NAME>
```

*Note: Be sure to replace `<BRICK_NAME>` with one of the following bricks:*

## Available bricks 🧱

| Brick Name       | Description                                                                                                                                                                                                 |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| feature_scaffold | Creates a new feature skeleton structure. Designed to go hand in hand with flutter_scaffold.  See [this](https://codewithandrea.com/articles/flutter-project-structure/) article for structure reasoning.   |
| flutter_scaffold | Sets up a skeleton structure for a new Flutter Project. See [this](https://codewithandrea.com/articles/flutter-project-structure/) article for structure reasoning.                                         |
| api_scaffold | Generates a skeleton structure for creating an API and testing it                                                                                                                                           | 