
# Overseer

Overseer is a reporting system for Minecraft servers, allowing players to easily report misconduct via commands. It supports both Java and Bedrock Editions, using GeyserMC/Cumulus for Bedrock UI.

## Features

- **Easy Reporting**: Simple commands for players to report misconduct.
- **Real-time Alerts**: Immediate notifications for administrators.
- **Detailed Logs**: All reports are logged for review.
- **Bedrock UI**: Supports Bedrock Edition UI via GeyserMC/Cumulus.
- **Discord Integration**: Reports can be sent to a Discord channel via WebHook.

## Installation

Installing Overseer is straightforward. Follow these steps:

1. Clone or download this repository:

   ```bash
   git clone https://github.com/ligfms/overseer.git
   ```

2. Place the files in your server's plugin directory.

3. Restart your server to ensure Overseer is correctly installed.

4. Configure the Discord WebHook URL in the `config.yml` file:

   ```yaml
   discord:
     webhook_url: "YOUR_DISCORD_WEBHOOK_URL"
   ```

## Usage

### Reporting Misconduct

Players can report misconduct using the following command:

```minecraft
/report <playername> <reason>
```

### Viewing Reports

Administrators can view reports using the following command:

```minecraft
/reports
```

### Bedrock Edition UI

For Bedrock Edition players, the UI is supported using GeyserMC/Cumulus. Ensure you have GeyserMC and Cumulus installed and configured on your server.

### Discord Integration

Reports will be sent to the specified Discord channel using the WebHook URL configured in the `config.yml` file.

## Support

Overseer is primarily intended for use on LFGMS servers. Support will not be provided unless there are critical issues. For general inquiries or non-critical issues, please refer to the community forums or documentation.

## Contributing

Contributions are welcome! Feel free to submit bug reports, feature requests, or pull requests to help improve Overseer.

## License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). See the LICENSE file for details.
