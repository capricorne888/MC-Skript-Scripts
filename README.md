# Minecraft Skript Scripts

Welcome to **Minecraft Skript Scripts**, a collection of custom Skript scripts designed for the Skript plugin on Minecraft servers. These scripts enhance your PaperMC server with unique features, mechanics, and utilities, all crafted to enrich gameplay and server management.

<p align="center">
  <img src="http://checkthese.com/img/IMG_0160.PNG?3" alt="Capricorne888" width="200" height="200">
</p>

## Overview

This repository contains a variety of custom Skript scripts tailored for use with the Skript plugin on PaperMC servers. Each script is designed to be easy to implement, well-documented, and optimized for performance. Whether you're adding new gameplay mechanics, automating server tasks, or creating unique player experiences, this collection has something for you.

### Tested Environment
All scripts in this repository have been tested and confirmed to work correctly on the following setup:
- **PaperMC**: Paper 1.21.4-221-main@c467df9 (2025-03-24T00:18:41Z)
- **Minecraft Version**: 1.21.4
- **Skript Version**: 2.10.2

## Features

- **Diverse Script Collection**: Includes scripts for gameplay enhancements, server utilities, custom mechanics, and more.
- **Plug-and-Play**: Scripts are ready to use with minimal configuration, designed for easy integration into your server.
- **Well-Documented**: Each script includes comments and instructions to help you understand and customize it.
- **Community-Driven**: Contributions and suggestions are welcome to expand the collection!

## Available Scripts

Below is a list of the scripts included in this repository (to be updated as I add scripts):

- **[NightVision]**: This simple script allow users with the permission to activate the night vision with a simple command.
- **[Console]**: This simple script allow server owner to send colorful message from the console.
- **[VoteWeather]**: This simple script allow users to vote for sun or rain.
- *More scripts to be added as I develop them!*

*Note*: Check the individual script files in the repository for detailed usage instructions and configuration options.

## Usage

To use these scripts, follow these steps:

1. **Install Dependencies**:
   - Ensure you have PaperMC (1.21.4) and Skript (2.10.2) installed on your server.
   - Download PaperMC from [papermc.io](https://papermc.io/) and Skript from [skriptlang.org](https://skriptlang.org/).

2. **Add Scripts**:
   - Copy the desired `.sk` script files from this repository into your server's `plugins/Skript/scripts/` folder.

3. **Reload Skript**:
   - Run the command `/sk reload <scriptname>` in-game or restart your server to load the scripts.

4. **Customize (Optional)**:
   - Open the `.sk` files in a text editor to adjust variables, permissions, or other settings as needed.

## Installation Example

```bash
# Example folder structure
server/
├── plugins/
│   ├── Skript/
│   │   ├── scripts/
│   │   │   ├── script1.sk
│   │   │   ├── script2.sk
│   │   │   └── script3.sk
```

After placing the scripts, reload them with:

```bash
/sk reload all
```

## Contributing

We welcome contributions! If you have a Skript script you'd like to add or an improvement to suggest:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature/new-script`).
3. Add your script or make changes.
4. Submit a pull request with a clear description of r contribution.

Please ensure your scripts are tested in the specified environment (PaperMC 1.21.4, Skript 2.10.2) and include proper documentation.

## Demo

*Coming Soon*: A demo server or video showcase demonstrating these scripts in action!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Note*: This README will be updated as new scripts are added to the repository. Check back regularly for the latest additions! If you have questions or need help, feel free to open an issue or reach out via the repository's discussion section.

