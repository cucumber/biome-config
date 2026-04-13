# biome-config

Base [Biome](https://biomejs.dev/) config for Cucumber's JavaScript projects.

## Usage

In your `biome.json`, start with this:

```json
{
  "$schema": "./node_modules/@biomejs/biome/configuration_schema.json",
  "extends": ["./node_modules/@cucumber/biome-config/base.json"]
}
```

You can then add rules, overrides etc which will be merged onto the shared config.
