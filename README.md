# Obsidian Svelte Plugin

This is a template repository for creating an Obsidian plugin using Svelte. It
provides a basic setup and structure to kickstart your development process.

Obsidian is a powerful note-taking and knowledge management application. With
the help of this template, you can create a plugin that extends Obsidian's
functionality using Svelte, a popular JavaScript framework for building user
interfaces.

## Features

- **Svelte** integration: Leverage the power of Svelte to build interactive and
  reactive user interfaces.
- **Easy setup**: Get started quickly with a pre-configured project structure
  and build setup.
- **Hot-reloading**: Enjoy fast development cycles with automatic reloading
  during development.
- **Example plugin**: Includes a basic example plugin to help you understand the
  structure and usage.

## Prerequisites

Before you get started, ensure that you have the following software installed:

- [Node.js](https://nodejs.org) (v14 or above)

## Getting Started

To create a new plugin using this template, follow these steps:

1. Click on the **"Use this template"** button at the top of the repository to
   create a new repository based on this template.
2. Clone the newly created repository to your local machine.
3. Open a terminal and navigate to the cloned repository.
4. Install the project dependencies by running the following command:

```bash
npm install
```

5. Start the development server with hot-reloading using the following command:

```bash
npm run dev
```

6. In **Obsidian**, open **Settings**.
7. In the side menu, select **Community plugins**.
8. Select **Turn on community plugins**.
9. Under **Installed plugins**, enable the **Obsidian Svelte Plugin** by
   selecting the toggle button next to it.
10. Start **building** your plugin by modifying the example plugin located in
    the src directory. You can also create new components and files as needed.
11. Once you're ready to bundle your plugin for **production**, run the
    following command:

```bash
npm run build
```

## Project Structure

The project structure follows a typical Svelte application structure with a few
additional files specific to Obsidian plugin development. Here's an overview:

- `src/` - Contains the source code for your plugin.
  - `main.ts` - The entry point for your plugin, initializes the plugin in
    Obsidian.
  - `ExamplePlugin.svelte` - An example Svelte component representing your
    plugin's user interface.
  - `styles/` - Directory for your Svelte component styles.
- `dist/` - The bundled output directory for your plugin generated by the build
  command.
- `manifest.json` - The plugin manifest file that describes your plugin's
  metadata.
- `LICENSE` - The license file for your plugin.
- `README.md` - This file, providing instructions on how to use the template.

## Resources

Here are some resources to help you get started with building plugins for
Obsidian:

- [Obsidian Plugin API Documentation](https://github.com/obsidianmd/obsidian-api)
- [Svelte Documentation](https://svelte.dev/docs)

## Contributing

If you encounter any issues or have suggestions for improvements, feel free to
open an issue or submit a pull request. Contributions are welcome!

## License

This template is available under the [MIT License](LICENSE). Feel free to modify
and use it to create your own Obsidian plugins.