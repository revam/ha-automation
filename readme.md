# Home Assistant Automation Blueprints (by revam)

So… this is the repository for my custom HA automation blueprints. Feel free to
use them as is, or just copy and modify them to your heart's desire.

## Available Blueprints

- `/events` — Event based automation blueprints.

  - `/rflink_button_events.yaml` — RFLink Button Events.
    <p>
      A simple automation blueprint to run actions when pressing the buttons on
      a RFLink button target with 'fire_event' set to true.
    </p>
    <a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A//github.com/revam/ha-automation/blob/main/blueprints/events/rflink_button_events.yaml" target="_blank" rel="noreferrer">
      <img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled."  style="width: 100%; max-width: 212px;"/>
    </a>

- `/lights` — Light based automation blueprints.

  - `/presence_light.yaml` — Presense-activated Light.
    <p>
      Turn on the lights when any kind of presence is detected, and
      turn them back off when no presence is detected after the wait time have
      elapsed. Works with three kinds of sensor types; Motion, moving & occupancy.
    </p>
    <a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A//github.com/revam/ha-automation/blob/main/blueprints/lights/presence_light.yaml" target="_blank" rel="noreferrer">
      <img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled."  style="width: 100%; max-width: 212px;"/>
    </a>

  - `/presence_light_with_pause.yaml` — Presense-activated Light with Pause.
    <p>
      Turn on the lights when any kind of presence is detected, and turn them
      back off when no presence is detected after the wait time have elapsed.
      Additionally, will pause the automation when a pause target is active.
      Works with three kinds of sensor types; Motion, moving & occupancy.
    </p>
    <a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A//github.com/revam/ha-automation/blob/main/blueprints/lights/presence_light_with_pause.yaml" target="_blank" rel="noreferrer">
      <img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled."  style="width: 100%; max-width: 212px;"/>
    </a>

## License

WTFPL, see [license.md](./license.md) for more info.
