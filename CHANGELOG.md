## [v0.0.10] - 2023-07-12


### New Feature Release
- Adding Agent Tools to LlamaHub (#377)

### Smaller features + Bug Fixes 
- Docugami: use metadata over deprecated extra_info (#375)

## [v0.0.9] - 2023-07-09

### Smaller features + Bug Fixes
- change readme and requirements (#354)
- Update zendesk loader (#358)
- Remove ascii in gmail loader (#361)
- Fix readme for wordlift (#357)
- address bug in paginated loader that always fetches the next page, even if the max_results is met (#363)
- S3 Extensions Filtering (#362)
- Add argument encoding to specify the encoding to open the csv file. (#367)
- Update README.md for unstructured (#366)
- fix bug where messages are returned without getting message data (#368)

## [v0.0.8] - 2023-07-04

### New Loaders
- Add firebase realtime db (#347)
- Add WordLift Loader (#346)

### Bug Fixes
- [bugfix] replace None to empty string to avoid TypeError (#351)
- chore: add youtube_id to document metadata (#352)

## [v0.0.7] - 2023-07-01

### Smaller features + Bug Fixes
- Add extra_info with Source to web reader (#337)
- support pagination on gmail loader (#348)


## [v0.0.6] - 2023-06-28

### Smaller features + Bug Fixes
- feat: add source metadata to documents created by the GH issues reader (#341)
- Update markdown reader (#344)
- ensure metadata always valid (#343)

## [v0.0.5] - 2023-06-26

### Major (Breaking) Changes
- update document usage (#338). NOTE: all Document objects must be prefixed with a `kwargs` field.

### New Loaders
- feat: add document reader for GH issues (#332)
- Add sitemap loader (#328)

### Bug Fixes
- Fixed ValueError: Metadata key must be str! error (#317)
- update namespace (#324)
- add changelog (#333)
- Fix KibelaReader (#334)
- confluence.load_data new features, bug fixes, tests (#330)
- Update readme files for reference (#336)


## [v0.0.4] - 2023-06-25

### New Loaders
- Add KibelaReader (#319)
- reader: add deplot tabular graph image reader (#321)

### Minor Changes / Bug Fixes
- support Confluence personal access token (#323)
- service account credentials (#316)

### Breaking/Deprecated API Changes
- None
 
### Miscellaneous 
- None