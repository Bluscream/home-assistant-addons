# PixelServ-TLS Add-on

A Home Assistant add-on for serving pixel GIFs over TLS.

## Installation

1. Add this repository to your Home Assistant instance:
   ```
   https://github.com/Bluscream/home-assistant-addons/tree/master/pixelserv-tls
   ```
2. Install the add-on through the UI
3. Configure options as needed
4. Start the add-on

## Configuration Options

| Option | Description | Default |
|--------|-------------|---------|
| log_level | Logging verbosity | info |
| http_port | Port number for HTTP traffic | 80 |
| https_port | Port number for HTTPS traffic | 443 |
| cert_dir | Certificate directory | /ssl |

## Support

For issues or feature requests, please open an issue on GitHub.