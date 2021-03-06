<div align=center><a href="https://github.com/lucka-me/MLP-android"><img src="./Resource/Banner.svg" alt="Banner"></a></div>

<h1 align=center>Changelog</h1>

```markdown
## [0.2.8] - 2018-09-06
- 0.2.7(231) -> 0.2.8(241)
- New function: Import from GPX

### Added
- Import GPX, parse with SAX, support wpt, trkpt, ele and desc.
```

```markdown
## [0.2.7] - 2018-09-05
- 0.2.6(210) -> 0.2.7(231)
- New function: Customizing providers

### Added
- Option: Mock Customized Provider
- Screen: Customized Provider, to manage the customized providers

### Changed
- Add license to select_dialog_item_material.xml, which is from android
- Methods of DialogKit minor modified
```

```markdown
## [0.2.6] - 2018-09-05
- 0.2.5(202) -> 0.2.6(210)
- New option: Confirm to Delete

### Added
- Confirm to Delete option, a snack bar with UNDO action will show up after
  deleting if the option is off
- Edit and remove icon under cards
```

```markdown
## [0.2.5] - 2018-09-04
- 0.2.4(200) -> 0.2.5(202)
- Bugs fixed

### Fixed
- Export Enabled Targets Only option works oppositely
- Imported targets displayed in wrong cards
```

```markdown
## [0.2.4] - 2018-09-04
- 0.2.3(188) -> 0.2.4(200)
- New feature: Import / export

### Added
- Import / export mock targets from / to JSON file using SAF
- Export Enabled Targets Only option in Preference
```

```markdown
## [0.2.3] - 2018-09-04
- 0.2.2(172) -> 0.2.3(188)
- New feature: Swipe to delete or edit

### Added
- Swipe left to delete
- Long press or swipe right to edit with Edit Mock Target Dialog

### Changed
- In Add Mock Target Dialog, check value immediately after input and the add
  button will enabled only when both values are valid and not being edited
```

```markdown
## [0.2.2] - 2018-09-03
- 0.2.1(156) -> 0.2.2(172)
- New feature: AddMockTargetDialog with tabs

### Added
- Tabs in AddMockTargetDialog: basic and advanced
- About screen

### Fixed
- FabAddMockTarget doesn't hide when scroll down
```

```markdown
## [0.2.1] - 2018-09-03
- 0.2(144) -> 0.2.1(156)
- Fixed: Incomplete location object

### Changed
- Swap the fabService and fabAddMockTarget
- FabService has two new icons

### Fixed
- Incomplete location object when sending mock location, accuracy is non-
  nullable and 5.0 for default now
```

```markdown
## [0.2] - 2018-09-02
- 0.1.4(115) -> 0.2(144)
- New data structure

### Added
- New attributes for MockTarget:
  - Title (UI and methods updated)
  - Inteval, accuracy and altitude (UI and methods not updated yet)
- Save / load data with the new DataKit and Gson

### Changed
- MockTarget is a data class now, the old data could NOT be migrated
```

```markdown
## [0.1.4] - 2018-09-02
- 0.1.2(62) -> 0.1.4(115)
- New feature: Preference, enable/disable providers

### Added
- Preference screen
- Enable and disable providers from receiving mock locations

### Changed
- App icon improved. Since the Assest Studio seems to not support some features
  of SVG, the icon is generated manually. Looking for a better way.
- Switch compileSdkVersion and targetSdkVersion to 27 temporarily for some
  unresolved issues
```

```markdown
## [0.1.2] - 2018-09-02
- 0.1.1(54) -> 0.1.2(62)
- New function: Detect Enable mock location option and alert

### Added
- Detect if the Enable mock location option turned on before starting service
- Alert if the option is off

### Changed
- Code documented
```

```markdown
## [0.1.1] - 2018-08-31
- 0.1(33) -> 0.1.1(54)
- Bug fixed

### Added
- Push notification when exception encountered
- Get service state by a better but not best way, with a method that deprecated
  but still working

### Changed
- All string resources are in English now

### Fixed
- Service won't update mock location if the last target is disabled
```

```markdown
## [0.1] - 2018-08-30
- 0.1(33)
- Initial version
```
