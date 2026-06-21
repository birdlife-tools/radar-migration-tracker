# Radar Migration Tracker

Extract bird migration patterns from weather radar data.

## Problem

Flocks of migratory birds move at night and are massive targets for meteorological radars. Biologists want this data in real-time to request temporary wind turbine shutdowns, but data is mixed with clouds and rain.

## Solution

Tool that pulls public binary radar data and applies filters removing meteorological phenomena, leaving only biological mass (bird flocks).

## Technical Stack

- Libraries `wradlib` or `pyart`
- Reflectivity and radial velocity analysis
- Mapping bird density per cubic kilometer

## Status

🚧 Planning

## License

MIT — see [LICENSE](LICENSE)
