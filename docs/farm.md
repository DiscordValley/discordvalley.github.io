# Farm Commands

The farm is the main focus of the game. From planting, to harvesting, to watering, this is where you will be making your money!.

!!! danger
    Some of these commands take more than one argument. Please make sure you give all arguments!

## Commands

| Command      | Description                          |
| :---------: | :----------------------------------: |
| ```farm```       | `farm` will show you your farm. This is important for you to check on the progress of your crops!|
| ```farm plant <plant name> [location]```       | A sub-command of farm. The seed must be in your inventory to use, and location can then be specified with as a grid. (ex: Top Left would be A1 plot coordinates on a small farm) |
| `farm harvest [plant name] [location]`    | A sub-command of farm. Running the `harvest` command will attempt to harvest your whole farm, leaving unfinished plants to keep growing. You can specify which crop to harvest with the plant name modifier, and specify which coordinate to harvest with the location modifier. (ex: Top Right would be A3 on a small farm) |
| `farm water [plant name] [location]`    | A sub-command of farm. Watering is essential to plant life, and watered plants will grow faster. Some plants may even die if not watered! You can specify which crop to water with the plant name modifier, and specify which coordinate to water with the location modifier (ex: Bottom Right would be C3 on a small farm).|
