# codespaces
Custom Codespace Templates

## Package Manager

This workspace is configured to use **Yarn** as the default package manager.

### Available Commands

- `yarn install` - Install dependencies
- `yarn add <package>` - Add a dependency
- `yarn add --dev <package>` - Add a development dependency
- `yarn remove <package>` - Remove a dependency
- `yarn run <script>` - Run a package.json script

### Configuration

- The workspace uses Yarn 1.22.22 as specified in `package.json`
- Yarn configuration is in `.yarnrc`
- Dependencies are locked in `yarn.lock`
- The dev container is configured to run `yarn install` on creation
