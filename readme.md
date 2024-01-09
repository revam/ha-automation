# Home Assistant Automation Blueprints (by revam)

So… this is the repository for my custom HA automation blueprints. Feel free to
use them as is, or just copy and modify them to your heart's desire.

## Available Blueprints

- `/lights` — Light based automation blueprints.

  - `/presense_light.yaml` — Presense-activated Light.
    <p>
      Turn on the lights when any kind of presence is detected, and
      turn them back off when no presence is detected after the wait time have
      elapsed. Works with three kinds of sensor types; Motion, moving & occupancy.
    </p>
    <a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A//github.com/revam/ha-automation/blob/main/blueprints/lights/presence_light.yaml" target='_blank' rel='noreferrer'>
      <img src='https://my.home-assistant.io/badges/blueprint_import.svg' alt='Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.'  style="width: 100%; max-width: 212px;"/>
    </a>

## License

WTFPL, see [license.md](./license.md) for more info.
