<a name="unreleased"></a>
## [Unreleased]


<a name="2021.10.23.1"></a>
## 2021.10.23.1 - 2021-10-23
### Docs
- **CHANGELOG.md:** updated changelog
- **CHANGELOG.md:** added config for commitizen
- **README.md:** Updated README.md

### Feat
- Added notification for washing machine pods
- Migrated front door lights automation
- Created automation for cleaning mode enable
- Enabled alerts
- Created alert for washing machine cleaning
- Added automation for washing machine start/finish
- Added automation for washing machine state
- Created automation for drysoon
- Created script for DrySoon notifications
- Node-RED flows updated
- Migrated Xbox automations from Node-RED
- **drysoon_manual_override.yaml:** created automation for drysoon override
- **drysoon_turn_off_drysoon.yaml:** automation for drysoon auto turn off
- **nespresso_lid.yaml:** created automation for nespresso lid
- **nespresso_vend_coffee.yaml:** added automation for coffee vend

### Fix
- Correcting template for sensor value
- Corrected input select thats used
- Corrected uuid for washing machine running automation
- Corrected notification message
- Correcting template for sensor value
- Correcting template for sensor value
- Set correct wait time after door closes
- Corrected hall lamp entity_id
- **nespresso_lid.yaml:** corrected state value for lid

### Refactor
- Removed washing machine and dishwasher energy sensors as these are now part of the integration
- Deleted auto_backup integration from configuration, relates to [#14](https://github.com/rj175/home-assistant-config/issues/14)

### Style
- Corrected linting issues
- Corrected linting issues with new automations


[Unreleased]: https://github.com/rj175/home-assistant-config/compare/2021.10.23.1...HEAD
