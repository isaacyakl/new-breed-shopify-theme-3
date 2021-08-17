# New Breed Shopify Theme v3

Shopify theme for [New Breed](https://newbreedpb.com) by [Yak](https://isaacyakl.com) based on the [Dawn](https://github.com/Shopify/dawn) theme.

References:

-  [Creating a theme based on Dawn](https://shopify.dev/themes/getting-started/create)
-  [Migrating a theme to Online Store 2.0](https://shopify.dev/themes/migration)
-  [Updating Shopify CLI](https://shopify.dev/apps/tools/cli/troubleshooting#rubygems-macos-linux-windows-10)

## Version

### [2021-08-16] 3.0.0

Fork [Dawn](https://github.com/Shopify/dawn) theme.

## To-Do

-  Setup GitHub CI Actions
-  Migrate/implement all features from theme versions [2.X.X](https://github.com/isaacyakl/new-breed-shopify-theme)

## Pull Upstream Changes

When Shopify makes improvements to the [Dawn](https://github.com/Shopify/dawn) theme, we can choose to implement those changes by adding the upstream (if it is not already setup):

```
git remote add upstream https://github.com/Shopify/dawn.git
```

And pulling updates as they are released:

```
git fetch upstream
git pull upstream main
```
