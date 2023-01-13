# Create Jigra Plugin

Generate a new Jigra plugin.

## Usage

```
npm init @jigra/plugin [<path>] [options]
```

:memo: `npm init <pkg>` requires npm 6+

You can also try the following methods to use this package:

- `npx @jigra/create-plugin`
- `yarn create @jigra/plugin`
- `npm install -g @jigra/create-plugin && create-jigra-plugin`

### Example Apps

As of the `0.8.0` release, example apps for testing are included when initializing a new plugin. To use these templates, you can open the `npx jig open android` or `npx jig open ios` command for Android and iOS respectively. Anything in the `example` folder will be excluded when publishing to npm.

### Options

```
--name <name> ............. npm package name (e.g. "jigra-plugin-example")
--package-id <id> ......... Unique plugin ID in reverse-DNS notation (e.g. "com.mycompany.plugins.example")
--class-name <name> ....... Plugin class name (e.g. "Example")
--repo <url> .............. URL to git repository (e.g. "https://github.com/example/repo")
--author <author> ......... Author name and email (e.g. "Name <name@example.com>")
--license <id> ............ SPDX License ID (e.g. "MIT")
--description <text> ...... Short description of plugin features
```
