## Farm Commands

Your main interaction in this game, right here in the farm. From planting, to harvesting, to watering, this is where you will be making your money! (Literally). 

!!! danger
    Some of these commands take more than one argument. Please make sure you give all arguments!

## Commands

| Command      | Description                          |
| :---------: | :----------------------------------: |
| `farm`       | `farm` will show you your farm. This is important for users to check on the farm and progress of your crops!|
| `farm plant [plant name] [optional:location]`       | A sub-command of farm is `plant`. The command will take two arguments, but only one is required. First is the seed name. The seed must be in your inventory to use. Then you can specify location with a normal grid. (ex: Top Left would be A1 plot coordinates on a small farm) |
| `farm harvest [optional:plant name] [optional:location]`    | A sub-command of farm is `harvest`. The command will take two arguments, but none are required. Running the `harvest` command will attempt to harvest your whole farm. Leaving unfinished plants to keep growing. You can specify which crop to harvest with the plant name modifier. You can also specify which coordinate to harvest with the location modifier. (ex: Top Right would be A3 on a small farm) |
| `farm water [optional:plant name] [optional:location]`    | A sub-command of farm is `water`. Watering is essential to plant life. You plants will grow faster if they are watered. Some plants my even die if they are not watered! You can specify which crop to water with the plant name modifier. You can also specify which coordinate to water with the location modifier. (ex: Bottom Right would be C3 on a small farm)|
