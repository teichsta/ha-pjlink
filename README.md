# Home Assistant - PJLink Integration

Custom component for Home Assistant to control projectors using the PJLink protocol.

This is a fork of the [PJLink integration](https://www.home-assistant.io/integrations/pjlink/) from Home Assistant Core, maintained by NEXABUS for custom fixes and enhancements.

## Installation

Install this custom component by adding the directory to your Home Assistant `custom_components` folder or via HACS.

## Configuration

Configure via the Home Assistant UI:

1. Go to Settings → Devices & Services
2. Click "Create Integration"
3. Search for "PJLink"
4. Enter the projector's host, port, and optional password

## Supported Features

- Turn projector on/off
- Volume mute/unmute
- Select input source
- Monitor projector state

## Requirements

- `pypjlink2>=1.2.1`

## Upstream

Original integration: [home-assistant/core/homeassistant/components/pjlink](https://github.com/home-assistant/core/tree/dev/homeassistant/components/pjlink)
