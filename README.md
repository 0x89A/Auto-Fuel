**Auto Fuel** simply lets fuel that is placed in tool cupboard inventories be shared around to active fuel sources.

Simply put fuel in a tool cupboard's inventory where that item is within its radius and any powered fuel sources *(lights, furnaces, etc.)* will automatically take their required fuel item/resource *(if it exists)* from the tool cupboard's inventory when needed. Keep in mind what type of fuel each fuel source requires and make sure to keep the tool cupboard stocked!

## Configuration

```json
{
  "Settings": {
    "Allowed objects": [
      "bbq.deployed",
      "campfire",
      "ceilinglight.deployed",
      "fireplace.deployed",
      "furnace",
      "furnace.large",
      "jackolantern.angry",
      "jackolantern.happy",
      "lantern.deployed",
      "refinery_small_deployed",
      "searchlight.deployed",
      "skull_fire_pit",
      "tunalight.deployed",
      "fogmachine",
      "snowmachine",
      "chineselantern.deployed"
    ],
    "Don't use fuel": false
  }
}
```

## Credits

- **rising_ace**, for the original idea via reddit
- **Retributive Law**, for helping with the testing
- **redBDGR**, original author of the plugin.
