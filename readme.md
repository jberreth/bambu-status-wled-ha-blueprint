# Bambu Status WLED Home Assistant Blueprint

This Home Assistant automation blueprint allows you to control one or more WLED light segments based on the status and stage of your Bambu Lab 3D printer.

## Features

- Automatically changes WLED light colors and effects based on printer status and stage.
- Supports multiple WLED light entities.
- Easy integration with Bambu Lab and WLED Home Assistant integrations.

## Usage

1. Copy the blueprint YAML file to your Home Assistant blueprints directory or [import it using the raw GitHub URL](https://www.home-assistant.io/docs/automation/using_blueprints/#importing-blueprints).
2. Create a new automation using this blueprint.
3. Select your Bambu Lab printer entities and WLED light entities as inputs.

## Inputs

- **Print Status**: Sensor entity for the print status.
- **Current Stage**: Sensor entity for the current stage.
- **Printer State**: Binary sensor entity for printer on/off state.
- **WLED Lights**: One or more WLED light entities to control.

## Example

```yaml
blueprint:
  source_url: https://raw.githubusercontent.com/jberreth/bambu-status-wled-ha-blueprint.yml
```

## Credits

- Based on [PaulBiod's HA-bambulab-wled.yaml](https://github.com/PaulBiod/HA-bambulab-wled).
- Modified by Jason Berreth.

---
