# MMM-TrainConnections
Additional Module for MagicMirror²  https://github.com/MichMich/MagicMirror/tree/v2-beta

# Module: Train Connections
This module displays trains from your favourit departurestation to any destination in Europe.

## Using the module

To use this module, add it to the modules array in the `config/config.js` file:
````javascript
modules: [
    {
		module: 'trainconnections',
		position: 'bottom_left',
		header: 'Zugverbindungen',
		config: {
			from: 'Bern', // Departure stations
			to: 'Paris', // Final Station
			maximumEntries: '6', // Max departures displayed
		}
	},
]
````


## Base API

This Modul is using the opendataCH/Transport API https://github.com/OpendataCH/Transport as apiBase
