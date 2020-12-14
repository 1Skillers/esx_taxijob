# esx_taxijob

ESX Taxi Job adds driving cabs as a service, and more including NPC missions.

## Requirements

* Auto mode
  * [esx_service](https://github.com/ESX-Org/esx_service)

* Player management (billing and boss actions)
  * [esx_society](https://github.com/ESX-Org/esx_society)
  * [esx_billing](https://github.com/ESX-Org/esx_billing)

## Download & Installation

### Manually
- Download https://github.com/1Skillers/esx_taxijob/archive/esx_taxijob.zip
- Put it in the `[esx]` directory

## Installation
- Import `esx_taxijob.sql` in your database
- If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`
- Add this to your `server.cfg`:
```
start esx_taxijob
```
