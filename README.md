**Auto Fuel** simply lets fuel that is placed in tool cupboard inventories be shared around to active fuel sources.

Simply put fuel in a tool cupboard's inventory where that item is within its radius and any powered fuel sources *(lights, furnaces, etc.)* will automatically take their required fuel item/resource *(if it exists)* from the tool cupboard's inventory when needed. Keep in mind what type of fuel each fuel source requires and make sure to keep the tool cupboard stocked!

## Configuration

```json
{
  "Types to autofuel": {
    "Use Barbeque": false,
    "Use Campfire": false,
    "Use Ceiling Light": true,
    "Use Furnace": false,
    "Use JackOLanterns": true,
    "Use Lantern": true,
    "Use Large Furnace": false,
    "Use Search Light": true,
    "Use Small Oil Refinery": false,
    "Use Tuna Can Lamp": true
  }
}
```

## Credits

- **rising_ace**, for the original idea via reddit
- **Retributive Law**, for helping with the testing
