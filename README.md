**Auto Fuel** simply lets fuel that is placed in tool cupboard inventories be shared around to active fuel sources.

Simply put fuel in a tool cupboard's inventory where that item is within its radius and any powered fuel sources *(lights, furnaces, etc.)* will automatically take their required fuel item/resource *(if it exists)* from the tool cupboard's inventory when needed. Keep in mind what type of fuel each fuel source requires and make sure to keep the tool cupboard stocked!

## Configuration

```json
{
  "Settings": {
    "Don't require fuel": false
  },
  "Types to autofuel": {
    "Use Barbeque": true,
    "Use Campfire": true,
    "Use Ceiling Light": false,
    "Use Fireplace": true,
    "Use Furnace": true,
    "Use JackOLanterns": false,
    "Use Lantern": false,
    "Use Large Furnace": true,
    "Use Search Light": false,
    "Use Skull Fire Pit": false,
    "Use Small Oil Refinery": true,
    "Use Tuna Can Lamp": false
  }
}
```

## Credits

- **rising_ace**, for the original idea via reddit
- **Retributive Law**, for helping with the testing
