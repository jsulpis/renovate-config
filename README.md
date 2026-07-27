# Renovate Config

Shared Renovate Bot Config Preset

## Usage

Use the app preset in an application's `renovate.json`:

```json
{
  "extends": ["github>jsulpis/renovate-config:apps"]
}
```

Use the library preset in a library's `renovate.json`:

```json
{
  "extends": ["github>jsulpis/renovate-config:libs"]
}
```

`base.json` contains the configuration shared by both presets. The default
preset (`github>jsulpis/renovate-config`) remains an alias for `apps`.
