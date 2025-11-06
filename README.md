# Hermes

A marketplace for Claude Code plugins that extends and enhances your Claude Code experience.

## Overview

Hermes is a curated collection of plugins designed to enhance Claude Code with additional capabilities, workflows, and tools. Each plugin in the marketplace provides specialized functionality that can be easily integrated into your Claude Code environment.

## Available Plugins

### Centauro

**Context Engineering Framework**

A professional context management framework implementing the C = A(c₁, c₂, c₃, c₄, c₅, c₆) methodology for systematic handling of context files.

- **Repository**: [elafo/centauro](https://github.com/elafo/centauro)
- **Use Case**: Managing and organizing context information for Claude Code interactions

### Ouroboros

**Meta-Recursive Toolkit for Claude Code Extensions**

A comprehensive toolkit for building, validating, and testing Claude Code extensions including Skills, Commands, Subagents, and Hooks. Features built-in validation, quality grading, and security review capabilities.

- **Repository**: [eLafo/ouroboros](https://github.com/eLafo/ouroboros)
- **Use Case**: Developing and maintaining Claude Code extensions with quality assurance

## Installation

Plugins in this marketplace are sourced from GitHub repositories. To install a plugin:

1. Navigate to the plugin's GitHub repository
2. Follow the installation instructions provided in the plugin's README
3. Configure the plugin according to its documentation

## Plugin Structure

Each plugin in the marketplace includes:

- **name**: Unique identifier for the plugin
- **description**: Brief overview of the plugin's functionality
- **source**: GitHub repository location

## Contributing

To add your plugin to the Hermes marketplace:

1. Ensure your plugin is hosted on GitHub
2. Prepare a clear description of your plugin's functionality
3. Submit a pull request updating `.claude-plugin/marketplace.json` with your plugin information

### Plugin Submission Format

```json
{
  "name": "your-plugin-name",
  "description": "Clear, concise description of what your plugin does",
  "source": {
    "source": "github",
    "repo": "username/repository"
  }
}
```

## Marketplace Metadata

- **Version**: 1.0.0
- **Plugin Root**: `./plugins`
- **Owner**: elafo

## License

Please refer to individual plugin repositories for their respective licenses.

## Support

For issues or questions:
- Plugin-specific issues: Open an issue in the respective plugin repository
- Marketplace issues: Open an issue in this repository
