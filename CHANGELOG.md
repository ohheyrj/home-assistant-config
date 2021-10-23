## Unreleased

### Feat

- Node-RED flows updated
- **drysoon_turn_off_drysoon.yaml**: automation for drysoon auto turn off
- **drysoon_manual_override.yaml**: created automation for drysoon override
- **nespresso_vend_coffee.yaml**: added automation for coffee vend
- **nespresso_lid.yaml**: created automation for nespresso lid
- Added automation for washing machine start/finish
- Added automation for washing machine state
- Created automation for drysoon
- Created script for DrySoon notifications
- Added notification for washing machine pods
- Created alert for washing machine cleaning
- Enabled alerts
- Created automation for cleaning mode enable
- Migrated front door lights automation
- Migrated Xbox automations from Node-RED

### Fix

- **nespresso_lid.yaml**: corrected state value for lid
- Corrected input select thats used
- Corrected uuid for washing machine running automation
- Corrected notification message
- Correcting template for sensor value
- Correcting template for sensor value
- Correcting template for sensor value
- Set correct wait time after door closes
- Corrected hall lamp entity_id

### Refactor

- Removed washing machine and dishwasher energy sensors as these are now part of the integration
- Deleted auto_backup integration from configuration, relates to #14
