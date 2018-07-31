# Changelog

All changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

- Notes about contacts.
- Fix 'Relationship' association with 'Contact'.

## [0.1.0] - 2018-07-31

### Added

- This changelog file was added.
- Logrus debug entries to more files.
- Additional fields in notes.
- README file.
- Relationships for contacts.
- Boolean input.
- Additional questions in contact creation.

### Changed

- 'client' commands and files were renamed to 'contact'.
- Using 'logrus.Fatal' instead of 'logrus.Fatalln' where possible.
- Joined 'contact add' and 'contact edit' commands.
- Contact fields.
- Changed maximum stars in hidden input hint.

### Fixed

- Debug command.