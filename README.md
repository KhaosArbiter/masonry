# 🧱 Masonry Bricks

Mason templates for boilerplate reduction

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

| Brick Name       | Description                                            |
|------------------|--------------------------------------------------------|
| feature_scaffold | Creates a new feature skeleton structure               |
| flutter_scaffold | Sets up a skeleton structure for a new Flutter Project |