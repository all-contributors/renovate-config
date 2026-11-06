# Renovate Configuration

Shared [Renovate](https://docs.renovatebot.com/) configuration for repositories in this organization.

## Usage

To use the shared configuration, add a `renovate.json` file to `.github` directory of the repo:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>all-contributors/renovate-config"]
}
```

Repositories can extend this configuration and define additional repository-specific settings as needed.

## Configuration

The default configuration is maintained in [`default.json`](./default.json).

Changes to the shared configuration are automatically picked up by repositories that extend it during subsequent Renovate runs.

## Resources

- [Renovate Documentation](https://docs.renovatebot.com/)
- [Configuration Options](https://docs.renovatebot.com/configuration-options/)
- [Shareable Configuration Presets](https://docs.renovatebot.com/config-presets/)
