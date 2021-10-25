<a name="unreleased"></a>
## [Unreleased]


<a name="2021.10.25.1"></a>
## [2021.10.25.1] - 2021-10-25
### Feat
- created input_boolean for gaming mode
- created automation for kitchen lights
- automations for dishwasher
- added uuid for automations
- **all_people.yaml:** created all_people group
- **away.yaml:** created automation when house is empty
- **home.yaml:** created automation when someone arrives home

### Fix
- added missing turn off of gaming mode
- **all_people.yaml:** removed test users from group
- **drysoon_turn_off_drysoon.yaml:** changed 'for' in trigger
- **lovelace.yaml:** removed dashboard

### Refactor
- deleted old automations for xbox
- deleted room scenes dashboard
- deleted overview dashboard

### Style
- **config.yml:** fixed linting error
- **xbox_event_lights.yaml:** linting issue

### Pull Requests
- Merge pull request [#46](https://github.com/rj175/home-assistant-config/issues/46) from rj175/xbox-lights-automation
- Merge pull request [#44](https://github.com/rj175/home-assistant-config/issues/44) from rj175/kitchen-lights
- Merge pull request [#45](https://github.com/rj175/home-assistant-config/issues/45) from rj175/remove-dashboard
- Merge pull request [#43](https://github.com/rj175/home-assistant-config/issues/43) from rj175/drysoon-changes
- Merge pull request [#41](https://github.com/rj175/home-assistant-config/issues/41) from rj175/unused-dashboards
- Merge pull request [#37](https://github.com/rj175/home-assistant-config/issues/37) from rj175/away-automation
- Merge pull request [#36](https://github.com/rj175/home-assistant-config/issues/36) from rj175/dishwasher-automation
- Merge pull request [#34](https://github.com/rj175/home-assistant-config/issues/34) from rj175/automations-uuid
- Merge pull request [#35](https://github.com/rj175/home-assistant-config/issues/35) from rj175/fix-linting


<a name="2021.10.23.1"></a>
## 2021.10.23.1 - 2021-10-23
### Docs
- **CHANGELOG.md:** updated changelog
- **CHANGELOG.md:** updated changelod
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

### Pull Requests
- Merge pull request [#33](https://github.com/rj175/home-assistant-config/issues/33) from rj175/drysoon
- Merge pull request [#32](https://github.com/rj175/home-assistant-config/issues/32) from rj175/nespresso
- Merge pull request [#31](https://github.com/rj175/home-assistant-config/issues/31) from rj175/changelog
- Merge pull request [#30](https://github.com/rj175/home-assistant-config/issues/30) from rj175/washing-machine
- Merge pull request [#29](https://github.com/rj175/home-assistant-config/issues/29) from rj175/washing-machine
- Merge pull request [#28](https://github.com/rj175/home-assistant-config/issues/28) from rj175/washing-machine
- Merge pull request [#27](https://github.com/rj175/home-assistant-config/issues/27) from rj175/washing-machine
- Merge pull request [#26](https://github.com/rj175/home-assistant-config/issues/26) from rj175/washing-machine
- Merge pull request [#25](https://github.com/rj175/home-assistant-config/issues/25) from rj175/washing-machine
- Merge pull request [#24](https://github.com/rj175/home-assistant-config/issues/24) from rj175/front-door-correct
- Merge pull request [#23](https://github.com/rj175/home-assistant-config/issues/23) from rj175/front-door-correct
- Merge pull request [#22](https://github.com/rj175/home-assistant-config/issues/22) from rj175/front-door
- Merge pull request [#21](https://github.com/rj175/home-assistant-config/issues/21) from rj175/remove-additional-energy-sensors
- Merge pull request [#13](https://github.com/rj175/home-assistant-config/issues/13) from rj175/xbox-automations
- Merge pull request [#15](https://github.com/rj175/home-assistant-config/issues/15) from rj175/auto-backup-remove


[Unreleased]: https://github.com/rj175/home-assistant-config/compare/2021.10.25.1...HEAD
[2021.10.25.1]: https://github.com/rj175/home-assistant-config/compare/2021.10.23.1...2021.10.25.1
