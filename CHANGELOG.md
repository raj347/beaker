# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- SiteData sqlite database now tracks information per origin
- History sqlite database now tracks visits
- Bookmarks and history UI
- Tab pinning and favicons
- URL navbar autocomplete
- API: beaker.fs

### Changed
- Restyled Browser UI
- Dat protocol: if index.html does not exist, but the archive was found, will now render the view-dat interface
- Moved bookmarks storage into a SQLite database
- Zoom now persists across navigations (using SiteData db)

### Fixed
- Fixed mimetype lookups when a file isnt identifiable by a magic number
- Fixed a bug that caused failed subresource fetches to register as a failed page-load